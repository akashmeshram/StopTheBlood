<template>
<div>
    <div class="row">
      <form class="col s12">
        <h3>Accident and Incident Register</h3>
        <div class="row">
          <div class="input-field col s6">
            <input id="incidate" type="text" class="datepicker">
            <label for="incidate">Date of incident (DD/MM/YYYY)</label>
          </div>
          <div class="input-field col s6">
            <input id="incitime" type="text" class="validate">
            <label for="incitime">Time of incident (HH:MM)</label>
          </div>
        </div>

        <div class="row">
          <div class="input-field col s8">
            <input id="first_name" type="text" class="validate">
            <label for="first_name">Injured person's name</label>
          </div>
          <div class="input-field col s4">
            <input id="injage" type="number" class="validate">
            <label for="injage">Injured person's age</label>
          </div>
        </div>

        <div class="row">
          <div class="input-field col s12">
           <textarea id="textarea1" class="materialize-textarea"></textarea>
          <label for="textarea1">Nature and type of the accident or incident </label>
          </div>
        </div>

        <div class="row">
          <div class="input-field col s12">
            <textarea id="textarea1" class="materialize-textarea"></textarea>
          <label for="textarea1">Cause of the accident or incident</label>
          </div>
        </div>
        <a class="waves-effect waves-light btn-large purple darken-3">Register</a>
      </form>
    </div>    
</div>
</template>

<script>
export default {
  name: 'Register',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
