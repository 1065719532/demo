<template>
  <section id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
    <footer-teb></footer-teb>
  </section>
</template>
<script>
import FooterTeb from '@/components/tebar'
export default {
  components: {FooterTeb}
}
</script>
<style lang="less">
</style>
