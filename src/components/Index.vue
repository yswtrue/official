
<template>
<div class="index">
  <hello></hello>
  <about></about>
</div>
</template>

<script>
import about from 'components/About'
import hello from 'components/Hello'
export default {
  name: 'index',
  components: {
    about,
    hello
  },
  data () {
    return {
      msg: '欢迎来到千人行工作室'
    }
  }
}
</script>
