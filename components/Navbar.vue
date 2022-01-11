<template>
  <nav>
    <ul class="nav-list">
      <li class="nav-list-item"><nuxt-link to="/settings">settings</nuxt-link></li>
      <li class="nav-list-item"><nuxt-link to="/logic">logic</nuxt-link></li>
      <li class="nav-list-item"><nuxt-link to="/questions">questions</nuxt-link></li>
      <li class="nav-list-item"><nuxt-link to="/respondent">respondets</nuxt-link></li>
      <li class="nav-list-item"><nuxt-link to="/">5</nuxt-link></li>
    </ul>
  </nav>
</template>

<style scoped>
nav{
    width: 100%;
}
.nav-list{
    padding: 0;
    margin: 0;
    list-style-type: none;
    display: flex;
    justify-content: space-evenly;
}
</style>