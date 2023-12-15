<template>
  <Head>
    <Link rel="canonical" :href="`https://voteshadow.com${$route.path}`" />
  </Head>

  <main>
    <NuxtPage />
  </main>
</template>

<script lang="ts" setup>
useHead({
  htmlAttrs: {
    lang: "en",
  },
  link: [
    {
      rel: "icon",
      type: "image/x-icon",
      href: "/favicon.ico",
    },
  ],
});
</script>

<style lang="scss">
body {
  margin: 0;
  min-width: 100%;
  min-height: 100%;
  position: absolute;
}
</style>

<style lang="scss" scoped>
main {
  display: flex;
  flex-direction: column;
}
</style>
