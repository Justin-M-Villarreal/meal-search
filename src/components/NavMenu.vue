
import HomePage from '@/views/HomePage.vue';
<template>
  <nav>
    <RouterLink to="{name: 'Home'}">Home</RouterLink>
    <RouterLink to="{name: 'MealsByName'}">Home</RouterLink>
    <RouterLink to="{name: 'MealsByLetter'}">Home</RouterLink>
    <RouterLink to="{name: 'MealsByIngredients'}">Home</RouterLink>
  </nav>
</template>

<style lang="postcss" scoped>
nav {
  @apply flex justify-center space-x-4;

  & .router-link-active {
    @apply underline underline-offset-4;
  }
}
</style>
