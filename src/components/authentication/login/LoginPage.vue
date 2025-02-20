<template>
  <div class="login">
    <div class="login__wrapper">
      <img class="login__img" :src="logo" alt="Logo" />

      <h1 class="login__title">Login To Your Dashboard</h1>

      <div class="login__inputs">
        <p>Email</p>
        <input placeholder="Input yout email" class="login__input" type="text" />

        <p>Password</p>
        <input placeholder="Input yout password" class="login__input" type="text" />
      </div>

      <button class="login__btn">Login</button>
    </div>
  </div>
</template>

<script lang="ts">
import './loginPage.scss'
import logo from '@/assets/logo.svg'

export default {
  name: 'LoginPage',
  data() {
    return {
      logo,
    }
  },
}
</script>
