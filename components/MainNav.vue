<!-- Please remove this file from your project -->
<template>
    <ul class="main-nav">
      <li
        v-for="(item, index) in mainNav" :key="index" class="main-nav-item">
        <a :href="item.route">
          <div class="main-nav-item_hed">{{ item.title }}</div>
          <span class="main-nav-item_sub">{{ item.subText }}</span>
        </a>
      </li>
    </ul>
</template>
<script>


import  { mainNavData } from  "@/assets/data.js"

export  default {
  data(){
    return {
      mainNav: mainNavData
    }
  }
};

</script>
