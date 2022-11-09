<template>
  <div class="slidev-layout cover text-center" :style="style">
    <div class="my-auto w-full">
      <slot />
    </div>
  </div>
</template>
  
<style lang="postcss">
.slidev-layout.cover {
background-image: url("/dark_background.jpeg");
background-repeat: no-repeat;
background-position: center;
background-size: cover;
padding: 4em 5em;
}

.slidev-layout.cover {
  h2 {
    color: var(--slidev-theme-secondary);
  }
}

</style>