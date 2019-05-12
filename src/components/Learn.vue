<template>
  <div class="row">
    <div class="col s3">
      <ul class="collection with-header">
        <li class="collection-header"><h4>Resources</h4></li>
        <li><a class="collection-item" v-on:click = "changeTab('how')">
            How to stop the bleeing.</a>
        </li>
        <li><a class="collection-item" v-on:click = "changeTab('stop')">
            Stop the bleed videos</a>
        </li>
        <li><a class="collection-item" href="#" v-on:click = "changeTab('register')">
            Flowchart</a>
        </li>
      </ul>        
    </div>
        
      <div class="col s9">     
          <div>
            <div v-if="currentTab == 'how'">
              <HowToStop />
            </div>
            <div v-if="currentTab == 'stop'">
              <StopVideo />
            </div>
            <div v-if="currentTab == 'register'">
              <StopVideo />
            </div>
        </div>
    </div>
  </div>   
</template>

<script>

import HowToStop from './learn/Howtostop.vue'
import StopVideo from './learn/Stopvideo.vue'

export default {
  name: 'Learn',
  components: {
    HowToStop,
    StopVideo
  },
  data: function() {
    return {
      currentTab: 'how'
    }
  },
  props: {
    msg: String
  },
  methods: {
    changeTab: function(val) {
      this.currentTab = val;
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .row {
    margin-top: 50px;
  }
</style>
