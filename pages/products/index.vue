<template>
    <div class="mt-5">
        <LargeCardSection
            v-for="cardInfo in largeCardSections.slice(0,1)"
            :key="cardInfo.id"
            :cardsSection="cardInfo"
        />
        <SmallCardSection
            v-for="cardInfo in smallCardSections"
            :key="cardInfo.id"
            :cardsSection="cardInfo"
        /> 
    </div>
</template>

<script>
import { largeCardSections, smallCardSections } from "@/assets/data.js"
    export default {
        data(){
            return {
                largeCardSections,
                smallCardSections
            }
        }
    }
</script>

<style scoped>
</style>