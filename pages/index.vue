<template>
    <div class="wrapper">
      <PortfolioRow
        v-for="x in portfolioObj"
        :key="x.id"
        :p-portfolio="x"
      />
    </div>
</template>
<script>
import  { portfolio } from  "@/assets/data.js"

export default {
      data(){
        return {
          portfolioObj: portfolio
        }
      }
}
</script>
