
<template>
<div class="index">
  <div class="banner">
    <top></top>
    <hello></hello>
  </div>
  <about></about>
</div>
</template>

<script>
import about from 'components/index/About'
import hello from 'components/index/Hello'
import top from 'components/index/Top'
export default {
  name: 'index',
  components: {
    about,
    hello,
    top
  },
  data: () => {
    return {
      msg: '欢迎来到千人行工作室'
    }
  }
}
</script>

<style media="screen">
.banner {
  height: 956px;
  background-size: cover;
  background-image: url('~assets/image/background.png');
}
</style>
