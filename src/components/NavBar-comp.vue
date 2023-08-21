<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <router-link class="navbar-brand" to="/"
        ><img
          src="https://i.postimg.cc/NMcMDYy1/Typography-Initial-Letter-Brand-Logo.png"
          alt="Appliance Cartel"
          class="navImage"
      /></router-link>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <router-link to="/" class="navButtons">Home</router-link>
          <router-link to="/products" class="navButtons"
            >Products</router-link
          >
          <router-link to="/about" class="navButtons">About</router-link>
          <router-link to="/contact" class="navButtons"
            >Contact</router-link
          >
          <router-link to="/admin" class="navButtons">Admin</router-link>
          <router-link to="/register" class="navButtons">Register</router-link>
          <button
              type="button"
              class="btn cart-btn"
              data-bs-toggle="modal"
              data-bs-target="#myModal"
              id="cart-btn"
            >
              <img
                src="https://i.postimg.cc/jqP7Nx5d/icons8-cart-100-1.png"
                alt="Cart"
                class="cart-img"
              />
            </button>
        </div>
      </div>
    </div>
  </nav>

 
</template>

 <script>
 export default {
 }
 </script>

 <style scoped>
 nav a{
    color: #EEEBDD;
    text-decoration: none;
 }

 .navImage, .cart-img {
    height: 60px;
 }

 </style>