<!-- Please remove this file from your project -->
<template>
  <div class="portfolio-item">
    <h1>Heading</h1>
    <p>Description</p>
  </div>
</template>

<script>
export  default {
  name: "PortfolioCard",
  data: () => ({
    items: [
      { title: 'Home', subText: "Overview" , route: '/'},
      { title: 'About' , subText: "A Protagonist by heart", route: '/career'},
      { title: 'Career' , subText: "The journey that made me", route: '/career'},
      { title: 'Web & Digital', subText: "What I know", route: '/web-digital'},
      { title: 'Contact',subText: "Lets have a call", route: '/contact'},
    ],
  }),

};
</script>
