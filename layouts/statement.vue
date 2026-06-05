<template>
  <div class="slidev-layout center h-full grid place-content-center statement">
    <div class="my-auto">
      <slot />
    </div>
    <div class="absolute bottom-4 right-8 text-sm opacity-50">
      {{ $page }}
    </div>
  </div>
</template>
