<template>
  <div>
    <div class="h-20 w-full"></div>
    <div class="text-gray-900">
      <div class="text-center py-8">
        <span> {{ doc.createdAt }}</span>
        <h1 class="text-5xl font-bold text-center">{{ doc.title }}</h1>
        <h4 class="text-2xl font-semibold">{{ doc.author }}</h4>
      </div>

      <div class="p-6 flex items-center justify-center mx-auto">
        <div class="w-full">
          <h1 class="text-3xl">{{ doc.description }}</h1>
          <nuxt-content class="my-4 text-gray-600" :document="doc" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $content, params }) {
    const doc = await $content(`news/${params.slug}`).fetch()
    return { doc }
  },
  head() {
    return {
      title: `${this.doc.title}`,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: `${this.doc.description}`,
        },
      ],
    }
  },
}
</script>