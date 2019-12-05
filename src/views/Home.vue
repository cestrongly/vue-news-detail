<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <audio id="myAudio" loop>
      <source src="horse.ogg" type="audio/ogg" />
      <source src="horse.mp3" type="audio/mpeg" />您的浏览器不支持 audio 与元素。
    </audio>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
