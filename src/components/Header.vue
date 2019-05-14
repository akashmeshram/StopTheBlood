<template>
    <div>
        <nav>
            <div class="nav-wrapper white">
                <a href="#" class="brand-logo"> &nbsp; STOP THE BLEED</a>
                <ul id="nav-mobile" class="right hide-on-med-and-down">
                    <li><a href="" v-on:click="$emit('OnClick', 'learn')">Learn</a></li>
                    <li><a href="" v-on:click="$emit('OnClick', 'train')">Train</a></li>
                    <li><a href="" v-on:click="$emit('OnClick', 'registry')">Register</a></li>
                    <li><a href="" class="waves-effect waves-light btn pink">Sign Up</a></li>
                </ul>
            </div>
        </nav>
        <img src="./images/sample-4.jpg">
    </div>
</template>
<script>
  export default {
      name: 'Header',
      props: {
          msg: String
      }
  }
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a,
.brand-logo {
    color: black;
}

img {
    display: block;
    width: 640px;
    height: 480px;
    margin-left: auto;
    margin-right: auto;
    margin-top: 5px;
}
</style>