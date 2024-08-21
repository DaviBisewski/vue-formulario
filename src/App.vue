<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
    

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/cadastro">Cadastro </RouterLink>
        <RouterLink to="/familia">Familia</RouterLink>
        <RouterLink to="/emprestimo">Emprestimo</RouterLink>
      </nav>
   
  </header>

  <RouterView />
</template>

<style scoped>

</style>
