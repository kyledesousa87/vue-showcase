<template>
  <div class="portfolio-item">
      <img class="img-thumb" :src="require(`@/assets/img/${ pCard.image || 'dude.jpg'}`)" alt="dude">
    <div class="portfolio-item_inner">
      <h1>{{ pCard.title }}</h1>
      <p>{{ pCard.desc }}</p>
    </div>
  </div>
</template>
<script>


export  default {
  props: {
    pCard: {
      type: Object,
      default: null
    }
  }
};
</script>



