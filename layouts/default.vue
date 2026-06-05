<template>
  <div class="slidev-layout h-full w-full">
    <slot />
    <div class="absolute bottom-4 right-8 text-sm opacity-50">
      {{ $page }}
    </div>
  </div>
</template>
