<template>
    <div class="mt-2">
        <h3>{{ cardsSection.title }}</h3>
        <b-row>
          <b-col class="card-img" cols="12" md="3" v-for="card in cardsSection.cards"
                :key="card.id">
        <SmallCard :card="card"/>
          </b-col>
        </b-row>
            
    </div>
</template>

<script>
    export default {
        props: ["cardsSection"]
    }
</script>

<style scoped>
.card-img{
        max-height: 12.5rem;
        overflow: hidden;
        padding:10px 5px;
}
</style>