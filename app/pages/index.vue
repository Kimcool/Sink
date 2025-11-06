<template>
  <div
    class="flex flex-col items-center justify-start min-h-screen bg-white text-gray-800 pt-10 sm:pt-12 md:-translate-y-4"
  >
    <h1 class="text-5xl sm:text-6xl font-extrabold mb-10 text-center text-gray-900">
      🚀 Welcome to <span class="text-blue-600">AFF</span>
    </h1>

    <main class="w-full max-w-7xl px-6 space-y-16">

      <!-- VPS 主机 -->
      <section id="vps">
        <h2 class="text-2xl font-semibold text-blue-600 mb-6 border-l-4 border-blue-600 pl-3">
          💻 VPS 主机
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a href="https://i.aff.dev/dmit" target="_blank"
             class="group block border border-gray-300 bg-white rounded-lg p-6 hover:bg-gray-50 transition">
            <div class="w-12 h-12 mb-4 flex items-center justify-center bg-gray-100 rounded-full text-2xl">
              🚀
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-900 group-hover:text-blue-600 transition">
              Dmit
            </h3>
            <p class="text-sm text-gray-600 leading-relaxed">
              美西、日本、香港线路，稳定可靠
            </p>
          </a>

          <a href="https://i.aff.dev/green" target="_blank"
             class="group block border border-gray-300 bg-white rounded-lg p-6 hover:bg-gray-50 transition">
            <div class="w-12 h-12 mb-4 flex items-center justify-center bg-gray-100 rounded-full text-2xl">
              🖥️
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-900 group-hover:text-blue-600 transition">
              Green VPS
            </h3>
            <p class="text-sm text-gray-600 leading-relaxed">
              美西、东南亚节点，价格实惠，活动多
            </p>
          </a>

          <a href="https://i.aff.dev/bwg" target="_blank"
             class="group block border border-gray-300 bg-white rounded-lg p-6 hover:bg-gray-50 transition">
            <div class="w-12 h-12 mb-4 flex items-center justify-center bg-gray-100 rounded-full text-2xl">
              🌏
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-900 group-hover:text-blue-600 transition">
              BandwagonHost
            </h3>
            <p class="text-sm text-gray-600 leading-relaxed">
              美西、日本、香港线路，上游是 Dmit，老牌稳定
            </p>
          </a>

          <a href="https://i.aff.dev/rfc" target="_blank"
             class="group block border border-gray-300 bg-white rounded-lg p-6 hover:bg-gray-50 transition">
            <div class="w-12 h-12 mb-4 flex items-center justify-center bg-gray-100 rounded-full text-2xl">
              ⚡
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-900 group-hover:text-blue-600 transition">
              RFC Host
            </h3>
            <p class="text-sm text-gray-600 leading-relaxed">
              香港、日本线路好，中国网络优化多
            </p>
          </a>
        </div>
      </section>

      <!-- 域名注册 -->
      <section id="domain">
        <h2 class="text-2xl font-semibold text-blue-600 mb-6 border-l-4 border-blue-600 pl-3">
          🌐 域名注册
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a href="https://www.namesilo.com/?rid=AFF1234" target="_blank"
             class="group block border border-gray-300 bg-white rounded-lg p-6 hover:bg-gray-50 transition">
            <div class="w-12 h-12 mb-4 flex items-center justify-center bg-gray-100 rounded-full text-2xl">
              🔗
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-900 group-hover:text-blue-600 transition">
              NameSilo
            </h3>
            <p class="text-sm text-gray-600 leading-relaxed">
              终身免费 WHOIS 隐私保护 · 支持支付宝
            </p>
          </a>

          <a href="https://www.dynadot.com/" target="_blank"
             class="group block border border-gray-300 bg-white rounded-lg p-6 hover:bg-gray-50 transition">
            <div class="w-12 h-12 mb-4 flex items-center justify-center bg-gray-100 rounded-full text-2xl">
              🪄
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-900 group-hover:text-blue-600 transition">
              Dynadot
            </h3>
            <p class="text-sm text-gray-600 leading-relaxed">
              域名优惠多 · 控制台简洁 · DNS 快速
            </p>
          </a>

          <a href="https://www.cloudflare.com/" target="_blank"
             class="group block border border-gray-300 bg-white rounded-lg p-6 hover:bg-gray-50 transition">
            <div class="w-12 h-12 mb-4 flex items-center justify-center bg-gray-100 rounded-full text-2xl">
              ☁️
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-900 group-hover:text-blue-600 transition">
              Cloudflare
            </h3>
            <p class="text-sm text-gray-600 leading-relaxed">
              安全稳定 · 提供免费域名解析
            </p>
          </a>

          <div class="flex items-center justify-center border border-dashed border-gray-300 rounded-lg bg-white p-6 text-gray-400">
            <span class="text-sm">更多即将上线…</span>
          </div>
        </div>
      </section>

    </main>

    <footer class="mt-16 text-sm text-gray-400">
      © 2025 AFF Hub · 部署于 Cloudflare Pages
    </footer>
  </div>
</template>


<script setup>
useHead({
  title: 'AFF - All For Future',
})</script>
