<template>
  <div className="flex flex-col min-h-screen overflow-hidden supports-[overflow:clip]:overflow-clip">

    <!-- Page content -->
    <main class="grow">

      <Hero />
      <IntegrationsList />
      <Cta />

    </main>

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import Hero from '../partials/IntegrationsHero.vue'
import IntegrationsList from '../partials/IntegrationsList.vue'
import Cta from '../partials/Cta04.vue'

export default {
  name: 'Integrations',
  components: {
    Header,
    Hero,
    IntegrationsList,
    Cta,
  },
}
</script>