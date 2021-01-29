<template>
  <div>
    <Hero />
    <LargeCardSection
    v-for="cardsSection in largeCardSections" :key="cardsSection.id"
    :cards-section="cardsSection"/>
    <SmallCardSection
    v-for="(cardsSection,index) in smallCardSections" :key="index"
    :cards-section="cardsSection"/>
  </div>
</template>

<script>
import {largeCardSections,smallCardSections} from "@/assets/data.js"
export default {
  data(){
    return {
      largeCardSections,
      smallCardSections
    }
  }
}
</script>

<style>

</style>
