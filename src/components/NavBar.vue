<template>
  <!-- style="background-color: #010101 -->
  <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
          <a class="navbar-brand ms-5 " href="#">
            <img class="logo-nav ms-5" src="../assets/logo-premiuminaja.png" alt="logo" width="98">
          </a>
      <div class="navbar-content">
          <ul class="navbar-nav p-lg-5">
            <li class="nav-item">
              <a class="nav-link active me-lg-5" style="color: #61BFAD;" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light me-lg-5" href="#">Product</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light me-lg-5" href="#">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light" href="#">Contact</a>
            </li>
          </ul>
        </div>
      </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar'

}
</script>

<style>
  .navbar{
    background-color: #010101;
    height: 90px;
  }

  .navbar-content{
    margin-right: 90px;
    
  }
  
</style>