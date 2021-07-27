<!-- Please remove this file from your project -->
<template>
  <svg version="1.1" class="k-logo" xmlns="http://www.w3.org/2000/svg" x="0" y="0" viewBox="0 0 36.5 49" xml:space="preserve">
    <path  class="k-logo__arrow" d="M36.5 12.2V0L0 24.5 36.5 49V36.8L18.2 24.5z" />
    <circle  class="k-logo__circ-top" cx="5" cy="44" r="5"/>
    <circle  class="k-logo__circ-bot" cx="5" cy="5" r="5"/>
  </svg>
</template>
<script>
    export  default {
      name: "MainNav",
      data: () => ({
        items: [
          { title: 'Home', subText: "Overview" , route: '/'},
          { title: 'About' , subText: "A Protagonist by heart", route: '/about'},
          { title: 'Career' , subText: "The journey that made me", route: '/career'},
          { title: 'Web & Digital', subText: "What I know", route: '/web-digital'},
          { title: 'Contact',subText: "Lets have a call", route: '/contact'},
        ],
      }),

    };
</script>
