<template>
<div>
  <div class="app">
    <Section />
  </div>
  <div class="section-two">
    <SectionTwo />
  </div>
  <div>
    <SectionThree />
  </div>
  <div>
    <SectionFour />
  </div>
</div>
</template>

<script>
import Section from './components/Section.vue'
import SectionTwo from './components/SectionTwo'
import SectionThree from './components/SectionThree'
import SectionFour from './components/SectionFour'

export default {
  name: 'App',
  components: {
    Section,
    SectionTwo,
    SectionThree,
    SectionFour
  }
}
</script>

<style>


</style>
