<template>
  <div class="flex flex-col items-center justify-center min-h-screen bg-gradient-to-br from-indigo-500 via-purple-500 to-pink-500 text-white relative">
    <h1 class="text-5xl sm:text-6xl font-extrabold mb-6 drop-shadow-lg text-center">
      🚀 Welcome to <span class="text-yellow-300">My Sink</span>!
    </h1>

    <!-- 机场导航区 -->
    <section class="grid grid-cols-1 sm:grid-cols-2 gap-5 max-w-3xl w-full px-6 mb-10">
      <a
        href="https://ssa.sx/lxy"
        target="_blank"
        class="block bg-white/10 backdrop-blur-md rounded-xl p-5 border border-white/20 hover:bg-white/20 transition"
      >
        <h3 class="text-xl font-semibold text-white mb-1">☁️ 良心云</h3>
        <p class="text-sm text-white/80">
          优质稳定的云服务 · 多条线路 · 按量计费
        </p>
      </a>

      <a
        href="https://ssa.sx/sntp"
        target="_blank"
        class="block bg-white/10 backdrop-blur-md rounded-xl p-5 border border-white/20 hover:bg-white/20 transition"
      >
        <h3 class="text-xl font-semibold text-white mb-1">🛡️ 守护网络</h3>
        <p class="text-sm text-white/80">
          安全可靠 · 7x24 支持 · 高性价比
        </p>
      </a>

      <a
        href="https://apps.apple.com/us/app/redteago-esim-travel-internet/id1492864476"
        target="_blank"
        class="block bg-white/10 backdrop-blur-md rounded-xl p-5 border border-white/20 hover:bg-white/20 transition"
      >
        <h3 class="text-xl font-semibold text-white mb-1">📱 红茶移动 RedteaGO</h3>
        <p class="text-sm text-white/80">
          邀请码：<b>MONS0030</b> · 全球 eSIM · 即买即用
        </p>
      </a>

      <a
        href="https://greencloudvps.com/billing/aff.php?aff=4451"
        target="_blank"
        class="block bg-white/10 backdrop-blur-md rounded-xl p-5 border border-white/20 hover:bg-white/20 transition"
      >
        <h3 class="text-xl font-semibold text-white mb-1">🖥️ GreenCloud VPS</h3>
        <p class="text-sm text-white/80">
          全球多机房 · 高性价比 · 灵活配置
        </p>
      </a>
    </section>

    <!-- 按钮组 -->
    <div class="flex flex-wrap gap-4 justify-center">
      <a
        href="/admin"
        class="bg-white text-indigo-700 font-semibold px-6 py-3 rounded-full shadow-lg hover:scale-105 hover:bg-indigo-50 transition-transform duration-200"
      >
        🛠 进入管理后台
      </a>

      <a
        href="https://github.com/ccbikai/sink"
        target="_blank"
        class="bg-transparent border border-white px-6 py-3 rounded-full hover:bg-white hover:text-indigo-700 transition duration-200"
      >
        ⭐ 项目源码
      </a>
    </div>

    <footer class="absolute bottom-5 text-sm text-white/80">
      © 2025 AFF · 部署于 Cloudflare Workers
    </footer>
  </div>
</template>

<script setup>
// 无需脚本逻辑，静态展示即可
</script>
