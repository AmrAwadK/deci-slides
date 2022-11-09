<script setup lang="ts">
const props = defineProps({
  class: {
    type: String,
  },
})
</script>

<template>
  <div class="slidev-layout two-columns w-full h-full">
    <div class="col-span-2 text-center">
      <slot />
    </div>
    <div class="grid grid-cols-2">
      <div class="col-left pr-20" :class="props.class">
        <slot name="left" />
      </div>
      <div class="col-right" :class="props.class">
        <slot name="right" />
      </div>
    </div>
  </div>
</template>
  
<style lang="postcss">
.slidev-layout.two-columns {
background-image: url("/light_background.jpg");
background-repeat: no-repeat;
background-position: center;
background-size: cover;
padding: 4em 5em;
}

.two-columns h2 {
    color: theme("colors.primary")
}
</style>