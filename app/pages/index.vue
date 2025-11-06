<template>
  <div class="min-h-screen bg-white text-gray-800 flex flex-col">
    <!-- 顶部导航栏 -->
    <nav
      class="w-full flex justify-between items-center px-6 sm:px-10 py-4 border-b border-gray-200 bg-white/80 backdrop-blur supports-[backdrop-filter]:bg-white/60 sticky top-0 z-10"
    >
      <a
        href="/"
        class="text-xl font-bold text-blue-600 hover:text-blue-700 transition"
      >
        🌐 AFF Hub
      </a>
      <div class="flex items-center gap-6 text-gray-700 text-sm sm:text-base">
        <a href="#vps" class="hover:text-blue-600 hover:underline underline-offset-4">VPS 主机</a>
        <a href="#domain" class="hover:text-blue-600 hover:underline underline-offset-4">域名注册</a>
        <a href="/dashboard" class="hover:text-blue-600 hover:underline underline-offset-4">仪表盘</a>
      </div>
    </nav>

    <!-- 主体内容 -->
    <div
      class="flex flex-col items-center justify-start flex-grow pt-8 sm:pt-12 md:-translate-y-6"
    >
      <!-- 标题 -->
      <h1
        class="text-5xl sm:text-6xl font-extrabold mb-10 text-center text-gray-900"
      >
        🚀 Welcome to <span class="text-blue-600">AFF</span>
      </h1>

      <main class="w-full max-w-6xl px-6 space-y-12">

        <!-- 💻 VPS 主机 -->
        <section id="vps">
          <h2
            class="text-2xl font-semibold text-blue-600 mb-4 border-l-4 border-blue-600 pl-3"
          >
            💻 VPS 主机
          </h2>

          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <a
              href="https://i.aff.dev/dmit"
              target="_blank"
              class="flex items-center gap-4 rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all duration-300 hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
            >
              <div
                class="flex-shrink-0 w-10 h-10 flex items-center justify-center text-xl bg-white rounded-lg shadow"
              >
                🚀
              </div>
              <div>
                <h3
                  class="text-lg font-semibold text-blue-600 mb-1 hover:underline hover:decoration-wavy hover:underline-offset-[5px]"
                >
                  Dmit
                </h3>
                <p class="text-sm text-gray-600">
                  美西、日本、香港线路，稳定可靠
                </p>
              </div>
            </a>

            <a
              href="https://i.aff.dev/green"
              target="_blank"
              class="flex items-center gap-4 rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all duration-300 hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
            >
              <div
                class="flex-shrink-0 w-10 h-10 flex items-center justify-center text-xl bg-white rounded-lg shadow"
              >
                🖥️
              </div>
              <div>
                <h3
                  class="text-lg font-semibold text-blue-600 mb-1 hover:underline hover:decoration-wavy hover:underline-offset-[5px]"
                >
                  Green VPS
                </h3>
                <p class="text-sm text-gray-600">
                  美西、东南亚节点，价格实惠，活动多
                </p>
              </div>
            </a>

            <a
              href="https://i.aff.dev/bwg"
              target="_blank"
              class="flex items-center gap-4 rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all duration-300 hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
            >
              <div
                class="flex-shrink-0 w-10 h-10 flex items-center justify-center text-xl bg-white rounded-lg shadow"
              >
                🌏
              </div>
              <div>
                <h3
                  class="text-lg font-semibold text-blue-600 mb-1 hover:underline hover:decoration-wavy hover:underline-offset-[5px]"
                >
                  BandwagonHost
                </h3>
                <p class="text-sm text-gray-600">
                  美西、日本、香港线路，上游是 Dmit，老牌稳定
                </p>
              </div>
            </a>

            <a
              href="https://i.aff.dev/rfc"
              target="_blank"
              class="flex items-center gap-4 rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all duration-300 hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
            >
              <div
                class="flex-shrink-0 w-10 h-10 flex items-center justify-center text-xl bg-white rounded-lg shadow"
              >
                ⚡
              </div>
              <div>
                <h3
                  class="text-lg font-semibold text-blue-600 mb-1 hover:underline hover:decoration-wavy hover:underline-offset-[5px]"
                >
                  RFC Host
                </h3>
                <p class="text-sm text-gray-600">
                  香港、日本线路好，中国网络优化多
                </p>
              </div>
            </a>
          </div>
        </section>

        <!-- 🌐 域名注册 -->
        <section id="domain">
          <h2
            class="text-2xl font-semibold text-blue-600 mb-4 border-l-4 border-blue-600 pl-3"
          >
            🌐 域名注册
          </h2>

          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <a
              href="https://www.namesilo.com/?rid=AFF1234"
              target="_blank"
              class="flex items-center gap-4 rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all duration-300 hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
            >
              <div
                class="flex-shrink-0 w-10 h-10 flex items-center justify-center text-xl bg-white rounded-lg shadow"
              >
                🔗
              </div>
              <div>
                <h3
                  class="text-lg font-semibold text-blue-600 mb-1 hover:underline hover:decoration-wavy hover:underline-offset-[5px]"
                >
                  NameSilo
                </h3>
                <p class="text-sm text-gray-600">
                  终身免费 WHOIS 隐私保护 · 支持支付宝
                </p>
              </div>
            </a>

            <a
              href="https://www.dynadot.com/"
              target="_blank"
              class="flex items-center gap-4 rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all duration-300 hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
            >
              <div
                class="flex-shrink-0 w-10 h-10 flex items-center justify-center text-xl bg-white rounded-lg shadow"
              >
                🪄
              </div>
              <div>
                <h3
                  class="text-lg font-semibold text-blue-600 mb-1 hover:underline hover:decoration-wavy hover:underline-offset-[5px]"
                >
                  Dynadot
                </h3>
                <p class="text-sm text-gray-600">
                  域名优惠多 · 控制台简洁 · DNS 快速
                </p>
              </div>
            </a>

            <a
              href="https://www.cloudflare.com/"
              target="_blank"
              class="flex items-center gap-4 rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all duration-300 hover:-translate-y-1 hover:shadow-lg hover:border-blue-400 hover:bg-gradient-to-br hover:from-blue-50 hover:to-purple-50"
            >
              <div
                class="flex-shrink-0 w-10 h-10 flex items-center justify-center text-xl bg-white rounded-lg shadow"
              >
                ☁️
              </div>
              <div>
                <h3
                  class="text-lg font-semibold text-blue-600 mb-1 hover:underline hover:decoration-wavy hover:underline-offset-[5px]"
                >
                  Cloudflare
                </h3>
                <p class="text-sm text-gray-600">
                  安全稳定 · 提供免费域名解析
                </p>
              </div>
            </a>
          </div>
        </section>
      </main>

    </div>
  </div>
</template>


<script setup>
useHead({
  title: 'AFF - All For Future',
})</script>
