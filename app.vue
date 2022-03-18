<script lang="ts" setup>
useMeta({
  meta: [
    {
      name: "viewport",
      content: "width=device-width, initial-scale=1, maximum-scale=1",
    },
  ],
  bodyAttrs: {
    class: "test",
  },
});
</script>
<template>
  <Html lang="es" class="dark">
    <Body class="m-0 p.0">
      <NuxtPage class="m-0 p.0 w-screen h-screen" />
    </Body>
  </Html>
</template>
