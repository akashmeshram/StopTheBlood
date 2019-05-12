<template>
  <div class="container">
    <Header/>
    <Navbar v-on:OnClick='changeTab'/>
    <div v-if= 'currenttab == "learn"'>
      <Learn />
    </div>
    <div v-if= 'currenttab == "train"'>
      <Train />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'
import Learn from './components/Learn.vue'
import Train from './components/Train.vue'

export default {
  name: 'app',
  components: {
    Header,
    Navbar,
    Learn,
    Train     
  },
  data: function () {
    return {
      currenttab: '',
    }
  },
  methods: {
    changeTab: function(val) {
      this.currenttab = val;
    }
  }
}
</script>

<style>
  @import './assets/materialize.min.css';

  img {
    height: 200px;
    width: 200px;
  }
</style>
