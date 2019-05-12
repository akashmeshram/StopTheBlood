<template>
  <div>
  	<h1>Train other by following</h1>
    
  	<div >
  		<br>
  		<h5>Choose a Video file or Document to upload</h5>
  		<form action="#" class="col s12">
		    <div class="file-field input-field">
		      <div class="btn">
		        <span>Click To upload</span>
		        <input type="file">
		      </div>
		      <div class="file-path-wrapper">
		        <input class="file-path validate" type="text">
		      </div>
		    </div>
		 </form>
		 <br>
		<h5>Your Information</h5>
		<form action="#">
		    <p>
		      <label>
		        <input class="with-gap" name="group1" type="radio"  />
		        <span>Certified</span>
		      </label>
		    </p>
		    <p>
		      <label>
		        <input class="with-gap" name="group1" type="radio"  />
		        <span>Not-Certified</span>
		      </label>
		    </p>
		</form>
	    <form class="col s12">
	      <div class="row">
	        <div class="input-field col s6">
	          <input id="first_name" type="text" class="validate">
	          <label for="first_name">First Name</label>
	        </div>
	        <div class="input-field col s6">
	          <input id="last_name" type="text" class="validate">
	          <label for="last_name">Last Name</label>
	        </div>
	      </div>
	      <div class="row">
	        <div class="input-field col s12">
	          <input id="password" type="password" class="validate">
	          <label for="password">Password</label>
	        </div>
	      </div>
	      <div class="row">
	        <div class="input-field col s12">
	          <input id="email" type="email" class="validate">
	          <label for="email">Email</label>
	        </div>
	      </div>
	    </form>
	</div>

  </div>
</template>

<script>
export default {
  name: 'Train',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
