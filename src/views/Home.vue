<template>
<div class="container">
    <NavBar></NavBar>
    <div class="columns">
      <div class="column is-one-third">
          <Menu></Menu>
      </div>
      <div class="column">
        <Content></Content>
      </div>
    </div>
    
    
  </div>
</template>

<script>

import Vue from "vue"
import Buefy from "buefy"
import "buefy/dist/buefy.css"
import NavBar from "@/components/NavBar.vue";
import Menu from "@/components/Menu.vue";
import Content from "@/components/Content.vue";

Vue.use(Buefy);

export default {
    components:{
      NavBar,
      Menu,
      Content
  }
};
</script>
