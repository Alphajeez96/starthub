<template>
  <div class="home">
   <hero></hero>
   <partners></partners>
  <services></services>
  <projects></projects>
  </div>
</template>

<script>
// @ is an alias to /src
import hero from '@/components/Home/hero'
import partners from '@/components/Home/partners'
import services from '@/components/Home/services'
import projects from '@/components/Home/projects'

export default {
  name: 'home',
  components: {
    hero, partners, services , projects
  }
}
</script>
