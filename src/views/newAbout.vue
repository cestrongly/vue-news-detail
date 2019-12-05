<template>
  <div>
    这是一个新的组件，从后台获取的数据={{value}}
  </div>
</template>

<script>
export default {
  name: 'newAbout',
  data () {
    return {
      value: ''
    }
  },
  created () {
    this.getData()
  },
  methods: {
    getData () {
      console.log('从后台获取数据开始')
      this.value = 'aaaa'
    }
  }
}
</script>

<style>
</style>
