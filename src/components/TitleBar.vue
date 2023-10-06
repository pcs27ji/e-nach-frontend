<template>
  <!-- <nav class="navbar navbar-expand-lg navbar-light bg-light"> -->
  <nav class="navbar navbar-expand-lg navbar-light">

    <div class="container">

      <!-- <router-link to="/" class="navbar-brand">Home</router-link> -->
      <!-- <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button> -->
      <div class="collapse navbar-collapse ml-auto" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/" class="nav-link" exact>Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link" exact>About</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/product" class="nav-link" exact>Product</router-link>
          </li>
        </ul>
      </div>
    </div>
    <div class="d-flex align-items-center">
       <div>
      <img class="companyImage" src="../assets/company-logo.png" alt="no aimage">
       </div>
      </div>
  </nav>
</template>

<script>
export default {
  name: 'TitleBar'
}
</script>

<style scoped>
.container {
  padding: 20px;
  margin-left: 40px;
}
.companyImage{
  margin: 15px 40px 0px 0px;
}
/* Add custom styles here */
</style>
