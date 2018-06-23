<!-- components/Navbar.vue -->

<template>
<section class="hero is-success">
	<div class="hero-head">
  <div class="container">
    <nav class="navbar is-fixed-top" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="/"><b>My Website :-p</b></a>
        
        <button class="button navbar-burger">
          <span></span>
          <span></span>
          <span></span>
        </button>
      </div>
      <div class="navbar-menu is-active">
        <div class="navbar-end">
          <nuxt-link class="navbar-item" to="/">Home</nuxt-link>
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link">
              Options
            </a>

            <div class="navbar-dropdown">
              <nuxt-link class="navbar-item" to="/add_item">
                <b>Add Item</b>
              </nuxt-link>
              <nuxt-link class="navbar-item" to="/del_item">
                <b>Delete Item</b>
              </nuxt-link>
              <nuxt-link class="navbar-item" to="/list_items">
                <b>View Items</b>
              </nuxt-link>
      
              </div>
            </div>

          <nuxt-link class="navbar-item" to="/login">Log In</nuxt-link>
          <nuxt-link class="navbar-item" to="/about">About</nuxt-link>
          <nuxt-link class="navbar-item" to="/contact">Contact</nuxt-link>
          
        </div>
      </div>
    </nav>
  </div>
</div>
</section>

</template>
<style>
.navbar-dropdown{
  color:black;

}


</style>
