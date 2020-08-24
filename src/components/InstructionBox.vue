<template>
  <div>
    <h1 class="text-4xl font-bold text-yellow-600">Hello Vue 3.0 + Vite + TailwindCSS</h1>

    <p
      class="py-3 text-xl font-bold text-gray-800"
    >There is no much to say, Vite simplified a lot of configurations 😅</p>

    <p>But you can find some in those files:</p>

    <ul class="py-3 text-left list-disc">
      <li>
        <b>postcss.config.js:</b> You can check here to install and configure css plugins (here is installed TailwindCSS and Autoprefixer)
      </li>
      <li>
        <b>tailwind.config.js:</b> Here is the tailwind configurations, check this link to see the options:
        <a
          class="text-yellow-600 underline"
          href="https://tailwindcss.com/docs/configuration"
        >TailwindCSS > Customization > Configuration</a>
      </li>
      <li>
        <b>eslintrc.js:</b> ESLint configs, that was created using the
        <span
          class="px-1 text-white bg-yellow-600 rounded-md"
        >eslint --init</span> command.
      </li>
    </ul>
  </div>
</template>

<script>
export default {
}
</script>
