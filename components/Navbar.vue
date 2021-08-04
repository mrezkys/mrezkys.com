<template>
<div>
  <b-navbar toggleable="lg" type="dark" variant="dark" class="navbar p-0 bg-transparent">
    <b-navbar-brand to="/" >
      <img  src="~assets/icons/mrezkyslogo.svg" alt="">
    </b-navbar-brand>
    <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
    <b-collapse id="nav-text-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item class="nav-item" to="/">Blog</b-nav-item>
        <b-nav-item class="nav-item" to="/">Projects</b-nav-item>
        <b-nav-item class="nav-item" to="/achievement">Achievement</b-nav-item>
        <b-nav-item class="nav-item" to="/">About Me</b-nav-item>
        <b-nav-item class="nav-item" to="/">Contact</b-nav-item>
        <b-nav-item class="nav-item" to="/" >Hire Me</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<style scoped>
  .navbar{
    padding: 20px 0 !important;
  }

  .nav-item{
    color: white;
    font-size: 18px;
    font-family: 'Poppins';
  }
</style>