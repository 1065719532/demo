<template>
  <section class="aa" @click="jump">
    123
  </section>
</template>

<script>
export default {
  data () {
    return {

    }
  },
  methods: {
    jump () {
      this.$router.push('../pages/demo')
    }
  },
  mounted () {
    let obj = {}
    obj.func = function (a) {
      return a = '123'
    }
    console.log(obj.func(1));
    
  }
}
</script>

<style>
.aa {
  display: flex;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
