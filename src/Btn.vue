<template>
  <button @click="$emit('click')"><slot></slot></button>
</template>

<script>
export default {};
</script>

<style scoped>
button {
  color: white;
  background-color: peru;
}
.rounded {
  border-radius: 10px;
}
</style>