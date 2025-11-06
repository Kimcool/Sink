<template>
  <div class="bg-white text-gray-800 pt-10 sm:pt-12 px-6">
    <h1 class="text-5xl sm:text-6xl font-extrabold mb-12 text-center text-gray-900">
      🚀 Welcome to <span class="text-blue-600">AFF</span>
    </h1>

    <main class="w-full max-w-7xl mx-auto space-y-16">

      <!-- 1️⃣ VPS 主机 -->
      <section id="vps">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-blue-500">
          VPS 主机
        </h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <!-- 8 个卡片示例 -->
          <a v-for="(item, i) in [
            {icon:'🚀',color:'from-blue-300 to-blue-100 text-blue-600',title:'Dmit',desc:'美西、日本、香港线路，稳定可靠'},
            {icon:'🖥️',color:'from-green-300 to-green-100 text-green-600',title:'Green VPS',desc:'美西、东南亚节点，价格实惠，活动多'},
            {icon:'🌏',color:'from-purple-300 to-purple-100 text-purple-600',title:'BandwagonHost',desc:'老牌 VPS，速度快，性价比高'},
            {icon:'⚡',color:'from-cyan-300 to-cyan-100 text-cyan-600',title:'RFC Host',desc:'香港、日本线路好，中国网络优化多'},
            {icon:'💡',color:'from-yellow-300 to-yellow-100 text-yellow-600',title:'Vultr',desc:'全球节点，计费灵活，适合开发测试'},
            {icon:'☁️',color:'from-indigo-300 to-indigo-100 text-indigo-600',title:'Hetzner',desc:'德国高性能 VPS，价格极具竞争力'},
            {icon:'🛰️',color:'from-rose-300 to-rose-100 text-rose-600',title:'AWS Lightsail',desc:'适合小型网站和轻量应用部署'},
            {icon:'🧭',color:'from-emerald-300 to-emerald-100 text-emerald-600',title:'Oracle Cloud',desc:'永久免费实例，适合个人使用'}
          ]" :key="i"
          href="#" class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 transition-all duration-300 hover:scale-[1.03] hover:shadow-lg">
            <div class="flex items-center gap-4 mb-5">
              <div :class="'w-10 h-10 flex items-center justify-center bg-gradient-to-tr rounded-md text-xl flex-shrink-0 '+item.color">
                {{item.icon}}
              </div>
              <h3 class="font-semibold text-lg sm:text-xl text-gray-900
                         group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]">
                {{item.title}}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{item.desc}}</p>
          </a>
        </div>
      </section>

      <!-- 2️⃣ 域名注册 -->
      <section id="domain">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-emerald-500">
          域名注册
        </h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a v-for="(item, i) in [
            {icon:'🔗',color:'from-blue-300 to-blue-100 text-blue-600',title:'NameSilo',desc:'终身免费 WHOIS 隐私保护 · 支持支付宝'},
            {icon:'🪄',color:'from-purple-300 to-purple-100 text-purple-600',title:'Dynadot',desc:'域名优惠多 · 控制台简洁 · DNS 快速'},
            {icon:'☁️',color:'from-cyan-300 to-cyan-100 text-cyan-600',title:'Cloudflare',desc:'提供免费域名解析与安全防护'},
            {icon:'💠',color:'from-green-300 to-green-100 text-green-600',title:'Google Domains',desc:'谷歌官方注册平台，管理简洁稳定'}
          ]" :key="i"
          href="#" class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 transition-all duration-300 hover:scale-[1.03] hover:shadow-lg">
            <div class="flex items-center gap-4 mb-5">
              <div :class="'w-10 h-10 flex items-center justify-center bg-gradient-to-tr rounded-md text-xl flex-shrink-0 '+item.color">
                {{item.icon}}
              </div>
              <h3 class="font-semibold text-lg sm:text-xl text-gray-900
                         group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]">
                {{item.title}}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{item.desc}}</p>
          </a>
        </div>
      </section>

      <!-- 3️⃣ 论坛相关 -->
      <section id="forum">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-orange-500">
          论坛相关
        </h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a v-for="(item, i) in [
            {icon:'💬',color:'from-blue-300 to-blue-100 text-blue-600',title:'LowEndTalk',desc:'知名 VPS 社区，发布优惠与测评'},
            {icon:'🧠',color:'from-indigo-300 to-indigo-100 text-indigo-600',title:'HostLoc',desc:'中文主机交流区，技术与优惠分享'},
            {icon:'📡',color:'from-emerald-300 to-emerald-100 text-emerald-600',title:'Reddit VPS',desc:'海外主机讨论区，技术干货多'},
            {icon:'📰',color:'from-rose-300 to-rose-100 text-rose-600',title:'WebHostingTalk',desc:'老牌主机论坛，行业资讯汇总'}
          ]" :key="i"
          href="#" class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 transition-all duration-300 hover:scale-[1.03] hover:shadow-lg">
            <div class="flex items-center gap-4 mb-5">
              <div :class="'w-10 h-10 flex items-center justify-center bg-gradient-to-tr rounded-md text-xl flex-shrink-0 '+item.color">
                {{item.icon}}
              </div>
              <h3 class="font-semibold text-lg sm:text-xl text-gray-900
                         group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]">
                {{item.title}}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{item.desc}}</p>
          </a>
        </div>
      </section>

      <!-- 4️⃣ 资源汇总 -->
      <section id="resources">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-purple-500">
          资源汇总
        </h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a v-for="(item, i) in [
            {icon:'📚',color:'from-blue-300 to-blue-100 text-blue-600',title:'Awesome Lists',desc:'开源资源合集，涵盖开发与网络工具'},
            {icon:'🧩',color:'from-green-300 to-green-100 text-green-600',title:'GitHub Tools',desc:'精选主机相关项目与工具'},
            {icon:'⚙️',color:'from-yellow-300 to-yellow-100 text-yellow-600',title:'Config Share',desc:'各类配置模板分享，便于快速部署'},
            {icon:'🎯',color:'from-rose-300 to-rose-100 text-rose-600',title:'SpeedTest.net',desc:'测速工具汇总，测试网络质量'}
          ]" :key="i"
          href="#" class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 transition-all duration-300 hover:scale-[1.03] hover:shadow-lg">
            <div class="flex items-center gap-4 mb-5">
              <div :class="'w-10 h-10 flex items-center justify-center bg-gradient-to-tr rounded-md text-xl flex-shrink-0 '+item.color">
                {{item.icon}}
              </div>
              <h3 class="font-semibold text-lg sm:text-xl text-gray-900
                         group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]">
                {{item.title}}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{item.desc}}</p>
          </a>
        </div>
      </section>
    </main>

  </div>
</template>



<script setup>
useHead({
  title: 'AFF - All For Future',
})</script>
