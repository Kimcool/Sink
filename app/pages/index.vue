<template>
  <div class="min-h-screen bg-gray-50 flex flex-col items-center justify-center py-16">
    <h1 class="text-4xl font-bold text-gray-800 mb-12">🚀 Welcome to AFF</h1>

    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8 max-w-7xl w-full px-6">

      <!-- 卡片示例 1 -->
      <a href="https://i.aff.dev/dmit"
         target="_blank"
         class="group relative bg-white rounded-2xl border border-gray-200 shadow-sm p-6 transition-all duration-300 hover:scale-[1.03] hover:shadow-lg">
        <!-- 圆形图标 -->
        <div
          class="w-10 h-10 flex items-center justify-center mb-4 rounded-full border-2 border-transparent bg-gradient-to-tr from-blue-300 to-blue-100">
          <span class="text-blue-500 text-xl">🚀</span>
        </div>

        <!-- 标题 -->
        <h3 class="text-gray-900 font-semibold text-lg mb-2">Dmit</h3>

        <!-- 描述 -->
        <p class="text-gray-600 text-sm leading-relaxed">
          美西、日本、香港线路，稳定可靠
        </p>

        <!-- 标签 -->
        <div class="mt-3 text-gray-400 text-xs space-x-2">
          <span># VPS</span>
          <span># CN2</span>
        </div>
      </a>

      <!-- 卡片示例 2 -->
      <a href="https://i.aff.dev/green"
         target="_blank"
         class="group relative bg-white rounded-2xl border border-gray-200 shadow-sm p-6 transition-all duration-300 hover:scale-[1.03] hover:shadow-lg">
        <div
          class="w-10 h-10 flex items-center justify-center mb-4 rounded-full border-2 border-transparent bg-gradient-to-tr from-green-300 to-green-100">
          <span class="text-green-500 text-xl">🖥️</span>
        </div>
        <h3 class="text-gray-900 font-semibold text-lg mb-2">Green VPS</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          美西、东南亚节点，价格实惠，活动多
        </p>
        <div class="mt-3 text-gray-400 text-xs space-x-2">
          <span># VPS</span>
          <span># 高性价比</span>
        </div>
      </a>

      <!-- 卡片示例 3 -->
      <a href="https://i.aff.dev/bwg"
         target="_blank"
         class="group relative bg-white rounded-2xl border border-gray-200 shadow-sm p-6 transition-all duration-300 hover:scale-[1.03] hover:shadow-lg">
        <div
          class="w-10 h-10 flex items-center justify-center mb-4 rounded-full border-2 border-transparent bg-gradient-to-tr from-purple-300 to-purple-100">
          <span class="text-purple-500 text-xl">🌏</span>
        </div>
        <h3 class="text-gray-900 font-semibold text-lg mb-2">BandwagonHost</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          美西、日本、香港线路，上游是 Dmit，老牌稳定
        </p>
        <div class="mt-3 text-gray-400 text-xs space-x-2">
          <span># VPS</span>
          <span># 稳定</span>
        </div>
      </a>

      <!-- 卡片示例 4 -->
      <a href="https://i.aff.dev/rfc"
         target="_blank"
         class="group relative bg-white rounded-2xl border border-gray-200 shadow-sm p-6 transition-all duration-300 hover:scale-[1.03] hover:shadow-lg">
        <div
          class="w-10 h-10 flex items-center justify-center mb-4 rounded-full border-2 border-transparent bg-gradient-to-tr from-cyan-300 to-cyan-100">
          <span class="text-cyan-500 text-xl">⚡</span>
        </div>
        <h3 class="text-gray-900 font-semibold text-lg mb-2">RFC Host</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          香港、日本线路好，中国网络优化多
        </p>
        <div class="mt-3 text-gray-400 text-xs space-x-2">
          <span># VPS</span>
          <span># 优化线路</span>
        </div>
      </a>

    </div>

  </div>
</template>





<script setup>
useHead({
  title: 'AFF - All For Future',
})</script>
