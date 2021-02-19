<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  },
  data() {
    return {
      a:1
    }
  },
  methods:{
    aaa():String{
      const a:Array<number> = [12312,12312];    
      return '123123';
   }
  }
})
export default class Home extends Vue {}
</script>
