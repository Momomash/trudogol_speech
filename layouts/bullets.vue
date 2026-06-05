<template>
  <div class="slidev-layout h-full grid bullets">
    <div class="pt-18">
      <slot />
    </div>
    <div class="absolute bottom-4 right-8 text-sm opacity-50">
      {{ $page }}
    </div>
  </div>
</template>
