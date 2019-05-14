<template>
  <div>
    <Header v-on:OnClick='changeTab'/>
    <div class="container">
      <Navbar v-on:OnClick='changeTab'/>
      <div v-if= 'currenttab == "learn"'>
        <Learn />
      </div>
      <div v-if= 'currenttab == "train"'>
        <Train />
      </div>
      <div v-if= 'currenttab == "registry"'>
        <Register />
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'
import Learn from './components/Learn.vue'
import Train from './components/Train.vue'
import Register from './components/Register.vue'

export default {
  name: 'app',
  components: {
    Header,
    Navbar,
    Learn,
    Train,
    Register
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
