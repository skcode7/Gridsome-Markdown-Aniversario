<template>
  <layout>
    <main role="main">
      <SectionHero />
      <!-- <Spotify /> -->
    </main>
  </layout>
</template>

<script>
import SectionHero from "@/components/SectionHero.vue"
// import Spotify from "@/components/Spotify.vue"
import { basicPageTransitionEnter, basicPageTransitionLeave } from "@/mixins/pageTransitions"

export default {
  metaInfo: {
    title: "Inicio"
  },
  components: {
    SectionHero
  },
  mixins: [basicPageTransitionEnter, basicPageTransitionLeave]
}
</script>
