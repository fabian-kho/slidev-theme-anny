<template>
  <div class="slidev-layout intro">
    <div class="my-auto w-full">
      <slot />
    </div>
  </div>
</template>


<style lang="postcss">
.slidev-layout.intro {
  @apply grid;

  h1 {
    @apply text-6xl leading-20;
  }

  h1 + p {
    @apply text-2xl -mt-6;
  }
}
</style>
<script setup>
</script>
