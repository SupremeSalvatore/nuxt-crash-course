<template>
  <div class="mb-3">
    <b-row>
      <b-col>
        <h2 class="header">
            {{ cardsSection.title }}
        </h2>
        <p class="lead" >
            {{ cardsSection.snippet }}
        </p>
      </b-col>
    </b-row>
    <b-row>
      <LargeCard 
      v-for="card in cardsSection.cards"
      :key="card.id"
      :card="card"
      />
    </b-row>
  </div>
</template>

<script>
export default {
    props: ['cardsSection']
}
</script>

<style scoped>
</style>