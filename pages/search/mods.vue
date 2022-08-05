<template>
  <div></div>
</template>

<script>
export default {
  name: 'Mods',
  asyncData(ctx) {
    ctx.params.projectType = 'mod'
  },
  head: {
    title: 'Mods - Feather',
    meta: [
      {
        hid: 'apple-mobile-web-app-title',
        name: 'apple-mobile-web-app-title',
        content: 'Mods',
      },
      {
        hid: 'og:title',
        name: 'og:title',
        content: 'Mods',
      },
      {
        hid: 'og:url',
        name: 'og:url',
        content: `https://feather-mod.vercel.app/mods`,
      },
    ],
  },
}
</script>

<style lang="scss" scoped></style>
