<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default{
  name: 'App',
  data(){
    
  },
  components:{
    AppHeader,
    AppMain,
    AppFooter
  },
  methods:{

  }
}
</script>

<template>
  <AppHeader/>
  <AppMain/>
  <AppFooter/>
</template>

<style lang="scss">
@import './styles/main.scss';
</style>
