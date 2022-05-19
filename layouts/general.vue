<script setup>
const route = useRoute()
const title = route.meta.title

</script>

<template>
  <div>
    <Head>
      <Title>{{ title }}</Title>
      <Style type="text/css" children="body { background-color: light-grey; }" />
    </Head>

    General Template

    <slot />

  </div>
</template>
