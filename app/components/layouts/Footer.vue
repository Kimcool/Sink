<script setup>
import { BloggerIcon, GitHubIcon, GmailIcon, MastodonIcon, TelegramIcon, XIcon } from 'vue3-simple-icons'

const { title, email, telegram, blog, twitter, mastodon, github } = useAppConfig()
</script>

<template>
  <section class="md:pt-6">
    <div
      class="
        container flex flex-col items-center py-8
        sm:flex-row
      "
    >
      <a
        href="https://i.aff.dev"
        class="
          text-xl leading-none font-black text-gray-900 select-none
          dark:text-gray-100
        "
        :title="title"
      >AFF</a>

        &copy; {{ new Date().getFullYear() }} 部署于 Cloudflare Workers

    </div>
  </section>
</template>
