<template>
  <section class="card">
    <p class="card__name">Name: Greg</p>
  </section>
</template>

<style scoped lang="scss">
@use '@/assets/style/vars' as *;
.card {
  width: clamp(300px, 75%, 600px);
  padding: $spacing-md;

  font-size: 18px;

  border-radius: $spacing-sm;
  background: $colour-grey-70;
}
</style>
