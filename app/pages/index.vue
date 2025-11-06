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
          <a
            v-for="(item, i) in vpsList"
            :key="i"
            :href="item.link"
            target="_blank"
            class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 hover:scale-[1.03] hover:shadow-lg transition-all duration-300"
          >
            <div class="flex items-center gap-4 mb-5">
              <div class="w-10 h-10 flex items-center justify-center rounded-md overflow-hidden flex-shrink-0">
                <img :src="item.logo" alt="logo" class="w-full h-full object-contain" />
              </div>
              <h3
                class="font-semibold text-lg sm:text-xl text-gray-900
                       group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]"
              >
                {{ item.title }}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{ item.desc }}</p>
          </a>
        </div>
      </section>

      <!-- 2️⃣ 域名注册 -->
      <section id="domain">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-emerald-500">
          域名注册
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a
            v-for="(item, i) in domainList"
            :key="i"
            :href="item.link"
            target="_blank"
            class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 hover:scale-[1.03] hover:shadow-lg transition-all duration-300"
          >
            <div class="flex items-center gap-4 mb-5">
              <div class="w-10 h-10 flex items-center justify-center rounded-md overflow-hidden flex-shrink-0">
                <img :src="item.logo" alt="logo" class="w-full h-full object-contain" />
              </div>
              <h3
                class="font-semibold text-lg sm:text-xl text-gray-900
                       group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]"
              >
                {{ item.title }}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{ item.desc }}</p>
          </a>
        </div>
      </section>

      <!-- 3️⃣ 论坛相关 -->
      <section id="forum">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-orange-500">
          论坛相关
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a
            v-for="(item, i) in forumList"
            :key="i"
            :href="item.link"
            target="_blank"
            class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 hover:scale-[1.03] hover:shadow-lg transition-all duration-300"
          >
            <div class="flex items-center gap-4 mb-5">
              <div class="w-10 h-10 flex items-center justify-center rounded-md overflow-hidden flex-shrink-0">
                <img :src="item.logo" alt="logo" class="w-full h-full object-contain" />
              </div>
              <h3
                class="font-semibold text-lg sm:text-xl text-gray-900
                       group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]"
              >
                {{ item.title }}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{ item.desc }}</p>
          </a>
        </div>
      </section>

      <!-- 4️⃣ 资源汇总 -->
      <section id="resources">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-purple-500">
          资源汇总
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a
            v-for="(item, i) in resourceList"
            :key="i"
            :href="item.link"
            target="_blank"
            class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 hover:scale-[1.03] hover:shadow-lg transition-all duration-300"
          >
            <div class="flex items-center gap-4 mb-5">
              <div class="w-10 h-10 flex items-center justify-center rounded-md overflow-hidden flex-shrink-0">
                <img :src="item.logo" alt="logo" class="w-full h-full object-contain" />
              </div>
              <h3
                class="font-semibold text-lg sm:text-xl text-gray-900
                       group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]"
              >
                {{ item.title }}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{ item.desc }}</p>
          </a>
        </div>
      </section>

      <!-- 5️⃣ eSIM 流量 -->
      <section id="esim">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-pink-500">
          eSIM 流量
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <a
            v-for="(item, i) in esimList"
            :key="i"
            :href="item.link"
            target="_blank"
            class="group block rounded-2xl border border-gray-200 bg-white shadow-sm p-5 hover:scale-[1.03] hover:shadow-lg transition-all duration-300"
          >
            <div class="flex items-center gap-4 mb-5">
              <div class="w-10 h-10 flex items-center justify-center rounded-md overflow-hidden flex-shrink-0">
                <img :src="item.logo" alt="logo" class="w-full h-full object-contain" />
              </div>
              <h3
                class="font-semibold text-lg sm:text-xl text-gray-900
                       group-hover:text-blue-600 group-hover:underline group-hover:decoration-wavy group-hover:underline-offset-[5px]"
              >
                {{ item.title }}
              </h3>
            </div>
            <p class="text-gray-600 text-sm leading-relaxed">{{ item.desc }}</p>
          </a>
        </div>
      </section>
    </main>

    <footer class="mt-16 text-sm text-gray-400 text-center">
      © 2025 AFF Hub · 部署于 Cloudflare Pages
    </footer>
  </div>
</template>

<script setup>
import { useHead } from '#imports'

useHead({
  title: 'AFF - All For Future',
  meta: [{ name: 'description', content: 'AFF Hub - VPS、域名、论坛与资源导航' }]
})

// VPS 主机
const vpsList = [
  { logo: '/logos/dmit.png', title: 'Dmit', link: 'https://i.aff.dev/dmit', desc: '美西、日本、香港线路，稳定可靠' },
  { logo: '/logos/green.png', title: 'Green VPS', link: 'https://i.aff.dev/green', desc: '美西、东南亚节点，价格实惠，活动多' },
  { logo: '/logos/bwg.png', title: 'BandwagonHost', link: 'https://i.aff.dev/bwg', desc: '老牌 VPS，速度快，性价比高' },
  { logo: '/logos/rfc.png', title: 'RFC Host', link: 'https://i.aff.dev/rfc', desc: '香港、日本线路好，中国网络优化多' },
  { logo: '/logos/vultr.png', title: 'Vultr', link: 'https://www.vultr.com', desc: '全球节点，计费灵活，适合开发测试' },
  { logo: '/logos/hetzner.png', title: 'Hetzner', link: 'https://www.hetzner.com', desc: '德国高性能 VPS，价格极具竞争力' },
  { logo: '/logos/aws.png', title: 'AWS Lightsail', link: 'https://aws.amazon.com/lightsail/', desc: '适合小型网站和轻量应用部署' },
  { logo: '/logos/oracle.png', title: 'Oracle Cloud', link: 'https://www.oracle.com/cloud/', desc: '永久免费实例，适合个人使用' }
]

// 域名注册
const domainList = [
  { logo: '/logos/namesilo.png', title: 'NameSilo', link: 'https://www.namesilo.com', desc: '终身免费 WHOIS 隐私保护 · 支持支付宝' },
  { logo: '/logos/dynadot.png', title: 'Dynadot', link: 'https://www.dynadot.com', desc: '域名优惠多 · 控制台简洁 · DNS 快速' },
  { logo: '/logos/cloudflare.png', title: 'Cloudflare', link: 'https://www.cloudflare.com', desc: '提供免费域名解析与安全防护' },
  { logo: '/logos/google.png', title: 'Google Domains', link: 'https://domains.google', desc: '谷歌官方注册平台，管理简洁稳定' }
]

// 论坛相关
const forumList = [
  { logo: '/logos/let.png', title: 'LowEndTalk', link: 'https://lowendtalk.com', desc: '知名 VPS 社区，发布优惠与测评' },
  { logo: '/logos/hostloc.png', title: 'HostLoc', link: 'https://hostloc.com', desc: '中文主机交流区，技术与优惠分享' },
  { logo: '/logos/reddit.png', title: 'Reddit VPS', link: 'https://www.reddit.com/r/vps/', desc: '海外主机讨论区，技术干货多' },
  { logo: '/logos/wht.png', title: 'WebHostingTalk', link: 'https://www.webhostingtalk.com', desc: '老牌主机论坛，行业资讯汇总' }
]

// 资源汇总
const resourceList = [
  { logo: '/logos/awesome.png', title: 'Awesome Lists', link: 'https://github.com/sindresorhus/awesome', desc: '开源资源合集，涵盖开发与网络工具' },
  { logo: '/logos/github.png', title: 'GitHub Tools', link: 'https://github.com/topics/vps', desc: '精选主机相关项目与工具' },
  { logo: '/logos/config.png', title: 'Config Share', link: '#', desc: '各类配置模板分享，便于快速部署' },
  { logo: '/logos/speedtest.png', title: 'SpeedTest.net', link: 'https://www.speedtest.net', desc: '测速工具汇总，测试网络质量' }
]

// eSIM 流量
const esimList = [
  { logo: '/logos/redteago.png', title: 'RedteaGO', link: 'https://redteago.com', desc: '全球 eSIM 流量服务，覆盖 200+ 国家地区' },
  { logo: '/logos/airalo.png', title: 'Airalo', link: 'https://www.airalo.com', desc: '全球 eSIM 流量服务，灵活套餐即买即用' },
  { logo: '/logos/ubigi.png', title: 'Ubigi', link: 'https://www.ubigi.com', desc: '多国 eSIM 支持，应用简洁' },
  { logo: '/logos/gigsky.png', title: 'GigSky', link: 'https://www.gigsky.com', desc: '适合国际旅行，流量价格友好' }
]
</script>
