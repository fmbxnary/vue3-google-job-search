<template>
  <button :class="{ primary: primary }">
    <!-- { primary } is a shorthand for { primary: primary } -->
    {{ text }}
  </button>
</template>

<script>
export default {
  name: "ActionButton",
  props: {
    text: {
      type: String,
      default: "Sign in",
    },
  },
  data() {
    return {
      primary: true,
    };
  },
};
</script>

<style scoped>
button {
  @apply rounded px-5 py-3 font-medium;
}

.primary {
  @apply border-0 bg-brand-blue-1 text-white hover:shadow-blue;
}

.seconday {
}
</style>
