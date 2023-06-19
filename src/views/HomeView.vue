<template>
  <main class="profile">
    <section class="profile__info">
      <h1 class="profile__title">Greg's Spotify Profile</h1>
      <p class="profile__description">
        This is just a nice sample description to be used to fill space lol
      </p>
    </section>
    <ProfileCard />
  </main>
</template>

<script setup lang="ts">
import ProfileCard from '@/components/ProfileCard.vue'
</script>

<style lang="scss" scoped>
@use '@/assets/style/vars' as *;

.profile {
  @include flex-x(center, center);
  width: 100%;
  height: 600px;
  gap: $spacing-xl;

  color: $colour-grey-20;

  &__title {
    margin-bottom: 24px;

    font-size: 48px;
    font-weight: 700;
  }
}
</style>
