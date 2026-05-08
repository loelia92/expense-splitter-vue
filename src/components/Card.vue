<template>
  <main class="card">
    <slot />
  </main>
</template>

<style scoped>
.card {
  width: min(600 px, 100%);
  background: #9c0303;
  padding: 18px;
  border-radius: 16px;
  box-shadow: 0 10px 24px rgba(156, 222, 205, 0.966);
}
</style>