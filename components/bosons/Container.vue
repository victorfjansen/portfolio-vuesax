<template>
  <div class="container">
    <slot />
  </div>
</template>

<style scoped>
.container {
  max-width: 1070px;
  margin: 0 auto;
}

@media (max-width: 1300px) {
  .container {
    max-width: 900px;
  }
}

@media (max-width: 1090px) {
  .container {
    max-width: 700px;
  }
}

@media (max-width: 900px) {
  .container {
    max-width: 500;
  }
}

@media (max-width: 700px) {
  .container {
    max-width: 300px;
  }
}
</style>
