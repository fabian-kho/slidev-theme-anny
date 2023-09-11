<template>
  <div class="slidev-layout default">
    <slot />
  </div>
</template>

<style lang="postcss" scoped>
.slidev-layout.default {
  background-image: var(--anny-slide);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  padding: 4em 5em;
}
</style>
