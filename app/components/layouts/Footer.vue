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
      <a
        class="
          mt-4 text-sm text-gray-500
          sm:mt-0 sm:ml-4 sm:border-l sm:border-gray-200 sm:pl-4
        "
        href="https://i.aff.dev"
        target="_blank"
        title="AFF"
      >
        &copy; {{ new Date().getFullYear() }} 部署于 Cloudflare Workers
      </a>
    </div>
  </section>
</template>
