<template>
  <div class="text-xl font-bold">
    <span class="text-4xl font-bold">{{ firstLetter(text) }}</span
    >{{ otherLetter(text) }}
  </div>
</template>

<script>
export default {
  name: 'IntroComponent',
  props: {
    text: {
      type: String,
      default: 'Default print',
      require: true,
    },
  },
  methods: {
    otherLetter(text) {
      return text.slice(1)
    },
    firstLetter(text) {
      return text.slice(0, 1)
    },
  },
}
</script>