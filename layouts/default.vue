<template>
  <div class="slidev-layout default" :style="style">
    <div class="my-auto w-full">
      <slot />
    </div>
  </div>
</template>
  
<style lang="postcss">
.slidev-layout.default {
background-image: url("/light_background.jpg");
background-repeat: no-repeat;
background-position: center;
background-size: cover;
padding: 4em 5em;
}

.default h1 {
  @apply text-center
}
</style>