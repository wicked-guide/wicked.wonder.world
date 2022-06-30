<template>
  <section>
    <h1>{{ title }}</h1>
  </section>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: 'たいとる',
    },
  },
}
</script>
