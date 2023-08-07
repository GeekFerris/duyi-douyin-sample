<script setup lang="ts">
import {RouterLink, RouterView} from 'vue-router'
import {NButton} from 'naive-ui'
import { useMessage } from 'naive-ui'
import router from "@/router";

function handleClick () {
  router.push('/duyi')
}

</script>

<template>
  <!--<header>-->
  <!--  <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125"/>-->

  <!--  <div class="wrapper">-->
  <!--    &lt;!&ndash;<HelloWorld msg="You did it!" />&ndash;&gt;-->

  <!--    <nav>-->
  <!--      &lt;!&ndash;<RouterLink to="/">Home</RouterLink>&ndash;&gt;-->
  <!--      &lt;!&ndash;<RouterLink to="/about">About</RouterLink>&ndash;&gt;-->
  <!--      <RouterLink to="/duyi">duyi</RouterLink>-->
  <!--      <RouterLink to="/duyi">duyi</RouterLink>-->
  <!--      <RouterLink to="/duyi">duyi</RouterLink>-->
  <!--    </nav>-->

  <!--  </div>-->
  <!--</header>-->
    <n-button @click="handleClick">1234</n-button>

  <RouterView></RouterView>
  <div>
    <n-button>3456</n-button>
  </div>



</template>

<style scoped>

</style>
