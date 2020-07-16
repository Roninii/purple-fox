<template>
  <div class="bg-white h-64 w-64 rounded shadow hover:shadow-lg">
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
