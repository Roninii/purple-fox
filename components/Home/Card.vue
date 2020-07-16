<template>
  <div
    class="bg-white h-64 w-64 rounded shadow hover:shadow-lg transition duration-300 transform hover:-translate-y-2 hover:scale-105"
  >
    Example {{ title }}
  </div>
</template>

<script>
export default {
  name: 'Card',
  props: {
    title: {
      type: String,
      default: '',
    },
  },
}
</script>
