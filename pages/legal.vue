<template>
  <div class="w-full mx-auto">
    <div class="h-32 w-full"></div>
    <headline class="mx-6 md:mx-8">{{ doc.title }}</headline>
    <div class="w-full max-w-5xl px-6 md:mx-auto md:my-16">
      <nuxt-content class="my-4 text-gray-600" :document="doc" />
    </div>
    <div class="mt-8 px-6 md:px-28 md:mx-auto">
      <Divider></Divider>
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $content, error }) {
    let doc
    try {
      doc = await $content('legal').fetch()
    } catch (e) {
      error({ message: 'Index content not found' })
    }
    return {
      doc,
    }
  },
  head() {
    return {
      title: `${this.doc.title}`,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: `Legal page description`,
        },
      ],
    }
  },
}
</script>