<template>
  <div
    class="flex flex-col items-center justify-center min-h-screen bg-white text-gray-800 pt-10 sm:pt-16"
  >
    <!-- 标题 -->
    <h1
      class="text-5xl sm:text-6xl font-extrabold mb-10 text-center text-gray-900"
    >
      🚀 Welcome to <span class="text-blue-600">AFF</span>
    </h1>

    <!-- A：机场服务 -->
    <section
      class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 max-w-5xl w-full px-6 mb-12"
    >
      <a
        href="https://i.aff.dev/dmit"
        target="_blank"
        class="block rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
      >
        <h3
          class="text-xl font-semibold mb-2 text-blue-600 hover:underline hover:underline-offset-4"
        >
          Dmit
        </h3>
        <p class="text-sm text-gray-600">
          美西、日本、香港线路，稳定可靠
        </p>
      </a>

      <a
        href="https://i.aff.dev/green"
        target="_blank"
        class="block rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
      >
        <h3
          class="text-xl font-semibold mb-2 text-blue-600 hover:underline hover:underline-offset-4"
        >
          Green VPS
        </h3>
        <p class="text-sm text-gray-600">
          美西、东南亚节点，价格实惠，活动多
        </p>
      </a>

      <a
        href="https://i.aff.dev/bwg"
        target="_blank"
        class="block rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
      >
        <h3
          class="text-xl font-semibold mb-2 text-blue-600 hover:underline hover:underline-offset-4"
        >
          BandwagonHost
        </h3>
        <p class="text-sm text-gray-600">
          美西、日本、香港线路，上游是 Dmit，老牌稳定
        </p>
      </a>

      <a
        href="https://i.aff.dev/rfc"
        target="_blank"
        class="block rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
      >
        <h3
          class="text-xl font-semibold mb-2 text-blue-600 hover:underline hover:underline-offset-4"
        >
          RFC Host
        </h3>
        <p class="text-sm text-gray-600">
          香港、日本线路好，中国网络优化多
        </p>
      </a>
    </section>

    <!-- B：域名注册 -->
    <section
      class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 max-w-5xl w-full px-6 mb-16"
    >
      <a
        href="https://www.namesilo.com/?rid=AFF1234"
        target="_blank"
        class="block rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
      >
        <h3
          class="text-xl font-semibold mb-2 text-blue-600 hover:underline hover:underline-offset-4"
        >
          NameSilo
        </h3>
        <p class="text-sm text-gray-600">
          终身免费 WHOIS 隐私保护 · 支持支付宝
        </p>
      </a>

      <a
        href="https://www.dynadot.com/"
        target="_blank"
        class="block rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
      >
        <h3
          class="text-xl font-semibold mb-2 text-blue-600 hover:underline hover:underline-offset-4"
        >
          Dynadot
        </h3>
        <p class="text-sm text-gray-600">
          域名优惠多 · 控制台简洁 · DNS 快速
        </p>
      </a>

      <a
        href="https://www.cloudflare.com/"
        target="_blank"
        class="block rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
      >
        <h3
          class="text-xl font-semibold mb-2 text-blue-600 hover:underline hover:underline-offset-4"
        >
          Cloudflare
        </h3>
        <p class="text-sm text-gray-600">
          安全稳定 · 提供免费域名解析
        </p>
      </a>
    </section>
  </div>
</template>

<script setup>
useHead({
  title: 'AFF - All For Future',
})</script>
