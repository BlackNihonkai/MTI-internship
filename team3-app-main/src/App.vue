<template>
  <div id="app">
    <Menu />
    <router-view/>
  </div>
</template>

<script>
  import {RouterView} from 'vue-router'
  import Menu from '@/components/Menu.vue';
  
  export default{
    name:'App',
    components:{
      //読み込んだコンポーネント名をここに記述
      Menu
    },
    computed:{
    }
  }
</script>