<script setup>

</script>

<template>
  <div class="wrapper">
    <header>
      <img class="menu" src="../assets/menu_alt.png" alt="menu" />
      <!-- <nav> -->
      <!--   <router-link to="/" exact>Home</router-link> -->
      <!--   <router-link to="/about">About</router-link> -->
      <!--   <router-link to="/contact">Contact</router-link> -->
      <!-- </nav> -->

      <img class="logo" src="../assets/teresinha.png" alt="Terezinha" />

      <div class="bell">
        <img class="bell_icon" src="../assets/bell.png" alt="Notification" />
        <div class="bell_dot"></div>
      </div>


      <!-- <div class="login-register"> -->
      <!--   <router-link to="/login">Login</router-link> -->
      <!--   <router-link to="/register">Register</router-link> -->
      <!-- </div> -->
    </header>
  </div>
</template>

<style scoped>

.wrapper {
  margin: 0;
  padding: 0;
  top: 0;
  left: 0;
}

.logo {
  width: 45px;
  height: 45px;
}

.menu {
  width: 24px;
  height: 19px;
}

.bell {
  position: relative;
  width: 19px;
  height: 19px;
}

.bell_icon {
  width: 100%;
  height: 100%;
}

.bell_dot {
  width: 5px;
  height: 5px;
  background-color: red;
  border-radius: 50%;
  position: absolute;
  top: 0;
  right: 0;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  background-color: #f3f3f3;
}

</style>
