<template>
  <div class="flex flex-col items-center justify-center min-h-screen bg-white text-gray-800">
    <!-- 标题 -->
    <h1 class="text-5xl sm:text-6xl font-extrabold mb-6 text-center text-gray-900">
      🚀 Welcome to <span class="text-blue-600">AFF</span>
    </h1>

    <!-- 机场服务导航 -->
    <section class="grid grid-cols-1 sm:grid-cols-2 gap-5 max-w-3xl w-full px-6">
      <a
        href="https://i.aff.dev/dmit"
        target="_blank"
        class="block bg-gray-50 rounded-xl p-5 border border-gray-200 hover:border-blue-400 hover:shadow transition"
      >
        <h3 class="text-xl font-semibold mb-1 text-blue-600">Dmit</h3>
        <p class="text-sm text-gray-600">
          美西、日本、香港线路，稳定可靠
        </p>
      </a>

      <a
        href="https://i.aff.dev/green"
        target="_blank"
        class="block bg-gray-50 rounded-xl p-5 border border-gray-200 hover:border-blue-400 hover:shadow transition"
      >
        <h3 class="text-xl font-semibold mb-1 text-blue-600">Green VPS</h3>
        <p class="text-sm text-gray-600">
          美西，东南亚，便宜，活动多
        </p>
      </a>

      <a
        href="https://i.aff.dev/bwg"
        target="_blank"
        class="block bg-gray-50 rounded-xl p-5 border border-gray-200 hover:border-blue-400 hover:shadow transition"
      >
        <h3 class="text-xl font-semibold mb-1 text-blue-600">Bandwagonhost</h3>
        <p class="text-sm text-gray-600">
          美西、日本、香港线路，很稳的，上游是 Dmit
        </p>
      </a>

      <a
        href="https://i.aff.dev/rfc"
        target="_blank"
        class="block bg-gray-50 rounded-xl p-5 border border-gray-200 hover:border-blue-400 hover:shadow transition"
      >
        <h3 class="text-xl font-semibold mb-1 text-blue-600">RFC Host</h3>
        <p class="text-sm text-gray-600">
          香港、日本线路好，中国网络优化多
        </p>
      </a>
    </section>

  </div>
</template>

<script setup>
useHead({
  title: 'All For Future',
})</script>
