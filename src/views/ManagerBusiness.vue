<template>
  <div class="container">
    <h1>Your Business Information</h1>
    <div class="row">
      <form class="col s12">
        <div class="row">
          <div class="input-field col s12">
            <input id="name" type="text" class="validate" value="Burger King">
            <label class="active" for="name">Name</label>
          </div>
          <div class="input-field col s12">
            <input id="city" type="text" class="validate" value="New York">
            <label class="active" for="city">City</label>
          </div>
          <div class="input-field col s12">
            <input id="city" type="text" class="validate" value="123 Wall St">
            <label class="active" for="city">Address</label>
          </div>
          <div class="">
            <h5>Business Score:</h5>
            <div class="center-align">
              <i class="material-icons grey-text">star</i>
              <i class="material-icons grey-text">star</i>
              <i class="material-icons grey-text">star</i>
              <i class="material-icons grey-text">star</i>
              <i class="material-icons">star_border</i>
            </div>
          </div>
          <div class="">
            <h5>Public Opinion:</h5>
            <div class="center-align">
              <i class="material-icons grey-text">star</i>
              <i class="material-icons grey-text">star</i>
              <i class="material-icons grey-text">star</i>
              <i class="material-icons grey-text">star_half</i>
              <i class="material-icons">star_border</i>
            </div>
          </div>
          <div class="input-field col s12">
            <router-link class="waves-effect waves-light btn lime darken-3" to="/manager/selfreport">
              Update Self Report
            </router-link>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ManagerBusiness',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1{
    font-size: 3rem;
  }

  .icon{
    display: block;
    margin: auto;
    margin-top: 3.5rem;
    margin-bottom: 3rem;
  }

  .btn{
    display: block;
    margin-top: 1rem;
  }
</style>
