<!-- Please remove this file from your project -->
<template>
  <ul class="main-nav">
      <li  v-for="(item, index) in items" :key="index" class="main-nav__link">
        <a :href="item.route">
          {{ item.title }}
          <span>{{ item.subText }}</span>
        </a>
      </li>
  </ul>
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
