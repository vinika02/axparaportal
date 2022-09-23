<template>
  <Header></Header>
  <SkillScanner></SkillScanner>
</template>

<script>
import Header from './components/includes/HeaderNav.vue'
import SkillScanner from './components/pages/SkillScanner.vue'

export default {
  name: 'App',
  components: {
    Header,
    SkillScanner,
  }
}
</script>

<style>
  html, body{
    background-color: #f5f5f5;
  }
</style>
