<template>
  <span>{{ label }}</span>
</template>

<script>
export default {
  name: "Title",
  props: {
    label: {
      type: String,
      default: "",
    },
  },
}
</script>

<style scoped>
span {
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 32px;
  color: #123952;
}
</style>
