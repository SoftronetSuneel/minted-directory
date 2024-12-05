<template>
  <div className="flex flex-col min-h-screen overflow-hidden supports-[overflow:clip]:overflow-clip">


    <!-- Page content -->
    <main class="grow">

      <Hero />
      <Story />
      <Team />
      <Recruitment />
      <Testimonials />
      <Cta />      

    </main>
 
  </div>
</template>

<script>
import Hero from '../partials/HeroAbout.vue'
import Story from '../partials/Story.vue'
import Team from '../partials/Team.vue'
import Recruitment from '../partials/Recruitment.vue'
import Testimonials from '../partials/Testimonials02.vue'
import Cta from '../partials/Cta02.vue'

export default {
  name: 'About',
  components: {
    Hero,
    Story,
    Team,
    Recruitment,
    Testimonials,
    Cta,
  },
}
</script>