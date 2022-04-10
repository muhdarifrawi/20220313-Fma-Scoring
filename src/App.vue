<template>
  <Navbar @clicked="onClickPage"></Navbar>
  <Main v-if="page==='main'"></Main>
  <AdminAndScore v-if="page === 'admin-score'" v-bind:="test"></AdminAndScore>
  <Keyform v-if="page === 'keyform'" :scoreData="scoreData"></Keyform>
  <Intervention v-if="page === 'intervention'"></Intervention>
  <Brochures v-if="page === 'brochures'"></Brochures>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Main from './components/Main.vue'
import AdminAndScore from './components/AdminAndScore.vue'
import Keyform from './components/Keyform.vue'
import Intervention from './components/Intervention.vue'
import Brochures from './components/Brochures.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Main,
    AdminAndScore,
    Keyform,
    Intervention,
    Brochures
  },
  data(){
    return{
      page:"admin-score",
    }
  },
  methods:{
    onClickPage(value){
      this.page = value;
    }
  }
}
</script>

<style>
  .custom-top-buffer{
        margin-top:55px;
        /* background: salmon; */
    }
  @media print{
    #main-navbar{
      display:none;
    }
    #part-3{
      display:block;  
    }
  }
</style>
