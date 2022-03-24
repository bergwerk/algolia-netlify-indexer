<template>
  <Tutorial/>
</template>

<script>
export default {
  name: 'IndexPage',
  head: {
    title: 'my website title',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'my website description'
      },
      {
        hid: 'og-title',
        name: 'og:title',
        content: 'my website og:title'
      }
    ],
  }
}
</script>
