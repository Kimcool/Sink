<template>
  <div
    class="flex flex-col items-center justify-center min-h-screen bg-white text-gray-800 pt-6 sm:pt-10 md:-translate-y-4"
  >
    <!-- 页面标题 -->
    <h1
      class="text-5xl sm:text-6xl font-extrabold mb-10 text-center text-gray-900"
    >
      🚀 Welcome to <span class="text-blue-600">AFF</span>
    </h1>

    <main class="w-full max-w-6xl px-6 space-y-12">

      <!-- 💻 VPS 主机 -->
      <section>
        <h2
          class="text-2xl font-semibold text-blue-600 mb-4 border-l-4 border-blue-600 pl-3"
        >
          💻 VPS 主机
        </h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
          <a href="https://i.aff.dev/dmit" target="_blank" class="card">
            <div class="icon">🚀</div>
            <div class="card-content">
              <h3>Dmit</h3>
              <p>美西、日本、香港线路，稳定可靠</p>
            </div>
          </a>

          <a href="https://i.aff.dev/green" target="_blank" class="card">
            <div class="icon">🖥️</div>
            <div class="card-content">
              <h3>Green VPS</h3>
              <p>美西、东南亚节点，价格实惠，活动多</p>
            </div>
          </a>

          <a href="https://i.aff.dev/bwg" target="_blank" class="card">
            <div class="icon">🌏</div>
            <div class="card-content">
              <h3>BandwagonHost</h3>
              <p>美西、日本、香港线路，上游是 Dmit，老牌稳定</p>
            </div>
          </a>

          <a href="https://i.aff.dev/rfc" target="_blank" class="card">
            <div class="icon">⚡</div>
            <div class="card-content">
              <h3>RFC Host</h3>
              <p>香港、日本线路好，中国网络优化多</p>
            </div>
          </a>
        </div>
      </section>

      <!-- 🌐 域名注册 -->
      <section>
        <h2
          class="text-2xl font-semibold text-blue-600 mb-4 border-l-4 border-blue-600 pl-3"
        >
          🌐 域名注册
        </h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
          <a href="https://www.namesilo.com/?rid=AFF1234" target="_blank" class="card">
            <div class="icon">🔗</div>
            <div class="card-content">
              <h3>NameSilo</h3>
              <p>终身免费 WHOIS 隐私保护 · 支持支付宝</p>
            </div>
          </a>

          <a href="https://www.dynadot.com/" target="_blank" class="card">
            <div class="icon">🪄</div>
            <div class="card-content">
              <h3>Dynadot</h3>
              <p>域名优惠多 · 控制台简洁 · DNS 快速</p>
            </div>
          </a>

          <a href="https://www.cloudflare.com/" target="_blank" class="card">
            <div class="icon">☁️</div>
            <div class="card-content">
              <h3>Cloudflare</h3>
              <p>安全稳定 · 提供免费域名解析</p>
            </div>
          </a>
        </div>
      </section>

    </main>

  </div>
</template>

<style scoped>
.card {
  @apply flex items-center gap-4 rounded-xl border border-gray-200 bg-gray-50 p-5 transition-all;
  transition: all 0.35s ease;
}
.card:hover {
  background: linear-gradient(135deg, #e0f2ff 0%, #f3e8ff 100%);
  transform: translateY(-4px);
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.12);
  border-color: #93c5fd;
}

/* 固定图标区域 */
.icon {
  flex-shrink: 0;
  width: 2.5rem;
  height: 2.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.5rem;
  background: white;
  border-radius: 0.75rem;
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.08);
}

/* 文字部分 */
.card-content h3 {
  font-size: 1.125rem;
  font-weight: 600;
  color: #2563eb;
  margin-bottom: 0.25rem;
  transition: all 0.2s;
}

/* Hover 时的锯齿下划线 + 距离 */
.card:hover h3 {
  text-decoration: underline wavy #2563eb 2px;
  text-underline-offset: 5px;
  text-decoration-thickness: 1.5px;
}

.card-content p {
  font-size: 0.875rem;
  color: #4b5563;
  line-height: 1.4;
}
</style>


<script setup>
useHead({
  title: 'AFF - All For Future',
})</script>
