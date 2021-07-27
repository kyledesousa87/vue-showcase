<!-- Please remove this file from your project -->
<template>
  <div class="portfolio">
    <h1>{{ pPortfolio.title }}</h1>
    <p>{{ pPortfolio.disc }}</p>
    <div class="portfolio-row">
      <PortfolioCard
        v-for="x in pPortfolio.item"
        :key="x.id"
        :p-card="x"
      />
    </div>
  </div>
</template>
<script>
export  default {
  props: {
    pPortfolio: {
      type: Object,
      default: null
    }
  }
};
</script>
