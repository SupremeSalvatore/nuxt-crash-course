<template>
  <b-col cols="12" md="4">
    <b-card
    :title="card.title"
    :img-src="require(`@/assets/images/${card.image || 'fe1.jpg'}`)"
    :img-alt="card.image"
    img-top
    tag="article"
    style="min-height: 500px"
    class="mb-2"
    >
      <b-card-text>
         {{card.snippet }}
      </b-card-text>
      <template #footer >
        <b-button  :to="`products/${card.id}`" variant="primary">See Product</b-button>
      </template>
    </b-card>
  </b-col>
</template>

<script>
    export default {
        props: ['card'],
    }
</script>

<style scoped>
  .card-img-top{
    height:275px;
  }
</style>