<template>
  <nav class="navbar navbar-expand-lg bg-black">
  <div class="container-fluid">
    <a class="nav-link active" aria-current="page" href="#">
      <img class="logo" src="../assets/lytus digital logo.png" >
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
      </ul>
        <p class="link-title">SOLUTIONS</p>
        <p class="link-title">CAREERS</p>
        <p class="link-title">CONTACT</p>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped >
 .navbar {
  z-index: 10;
  border-bottom: 2px solid cyan;
 }

 .logo {
    cursor: pointer;
    width: 200px;
    height: 70px;
    object-fit: contain;
  }

  .link-title {
    font-size: 16px;
    display: inline;
    color: white;
    margin: 10px;
    cursor: pointer;
    transition: color 0.4s;
  }

  .link-title:hover {
    color: cyan;
  }
</style>