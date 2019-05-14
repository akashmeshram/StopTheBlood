<template>
  <div class="row">
      <div class="col s4 ">
        <a href="#" v-on:click="$emit('OnClick', 'learn')">
          <div class="card hoverable">
            <div class="card-image">
              <img src="./images/sample-1.png">
            </div>
            <div class="card-content">
              <p>Learn </p>
            </div>
          </div>
        </a>
      </div>

      <div class="col s4">
        <a href="#" v-on:click="$emit('OnClick', 'train')">
          <div class="card hoverable">
            <div class="card-image">
              <img src="./images/sample-5.jpg">
            </div>
            <div class="card-content">
              <p>Train</p>
            </div>
          </div>
        </a>
      </div>

      <div class="col s4">
        <a href="#" v-on:click="$emit('OnClick', 'registry')">
          <div class="card hoverable">
            <div class="card-image">
              <img src="./images/sample-3.jpg">
            </div>
            <div class="card-content">
              <p>Registry </p>
            </div>
          </div>
        </a>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  p {
    text-align: center;
    font-size: 25px;
  }

</style>
