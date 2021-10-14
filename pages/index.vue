<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="title text-center">Nuxt — Tailwind — Netlify CMS</h1>
      <h2 class="subtitle text-center">Let's start working</h2>
    </section>

    <!-- <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Latest blog post</h3>
      <posts post-type="blog" :amount="1" />
    </section> -->

    <section>
      <intro-component text="About the life of Hamburg is good"> </intro-component>
      <pharagraph>
        <template slot="content">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec finibus auctor massa, vitae posuere sem
          tincidunt eget. Duis non vestibulum diam. Pellentesque eleifend interdum mollis. Donec porttitor dui enim.
          Maecenas a semper sem. Nunc molestie turpis vitae sem auctor, non venenatis velit ultricies.
        </template>
      </pharagraph>
    </section>
  </main>
</template>