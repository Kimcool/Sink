<template>
  <div class="flex flex-col items-center justify-center min-h-screen bg-white text-gray-800">
    <!-- 标题 -->
    <h1 class="text-5xl sm:text-6xl font-extrabold mb-6 text-center text-gray-900">
      🚀 Welcome to <span class="text-blue-600">AFF</span>
    </h1>

    <!-- 机场服务导航 -->
    <section class="grid grid-cols-1 sm:grid-cols-2 gap-5 max-w-3xl w-full px-6">
      <a
        href="https://a.aff.dev/dmit"
        target="_blank"
        class="block bg-gray-50 rounded-xl p-5 border border-gray-200 hover:border-blue-400 hover:shadow transition"
      >
        <h3 class="text-xl font-semibold mb-1 text-blue-600">Dmit</h3>
        <p class="text-sm text-gray-600">
          优质稳定的云服务 · 多条线路 · 按量计费
        </p>
      </a>

      <a
        href="https://a.aff.dev/green"
        target="_blank"
        class="block bg-gray-50 rounded-xl p-5 border border-gray-200 hover:border-blue-400 hover:shadow transition"
      >
        <h3 class="text-xl font-semibold mb-1 text-blue-600">Green VPS</h3>
        <p class="text-sm text-gray-600">
          安全可靠 · 7x24 支持 · 高性价比
        </p>
      </a>

      <a
        href="https://apps.apple.com/us/app/redteago-esim-travel-internet/id1492864476"
        target="_blank"
        class="block bg-gray-50 rounded-xl p-5 border border-gray-200 hover:border-blue-400 hover:shadow transition"
      >
        <h3 class="text-xl font-semibold mb-1 text-blue-600">📱 红茶移动 RedteaGO</h3>
        <p class="text-sm text-gray-600">
          邀请码：<b>MONS0030</b> · 全球 eSIM · 即买即用
        </p>
      </a>

      <a
        href="https://greencloudvps.com/billing/aff.php?aff=4451"
        target="_blank"
        class="block bg-gray-50 rounded-xl p-5 border border-gray-200 hover:border-blue-400 hover:shadow transition"
      >
        <h3 class="text-xl font-semibold mb-1 text-blue-600">🖥️ GreenCloud VPS</h3>
        <p class="text-sm text-gray-600">
          全球多机房 · 高性价比 · 灵活配置
        </p>
      </a>
    </section>

    <!-- 页脚 -->
    <footer class="mt-12 text-sm text-gray-400">
      © 2025 AFF · 部署于 Cloudflare Workers
    </footer>
  </div>
</template>

<script setup>
// 无需逻辑，仅静态展示
</script>
