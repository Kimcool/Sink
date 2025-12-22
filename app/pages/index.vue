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

      <!-- 5️⃣ 新鲜有趣 -->
      <section id="esim">
        <h2 class="text-2xl font-semibold text-gray-900 mb-6 pl-3 border-l-4 border-pink-500">
          新鲜有趣
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

  </div>
</template>

<script setup>
import { useHead } from '#imports'

useHead({
  title: 'AFF - All For Future',
  meta: [{ name: 'description', content: 'Future is ours' }]
})

// VPS 主机
const vpsList = [
  { logo: '/dmit.webp', title: 'Dmit', link: 'https://aff.dev/dmit', desc: '美西、日本、香港线路，稳定可靠' },
  { logo: '/green.jpg', title: 'Green VPS', link: 'https://aff.dev/green', desc: '美西、东南亚节点，价格实惠，活动多' },
  { logo: '/bwg.jpg', title: '搬瓦工', link: 'https://aff.dev/bwg', desc: '老牌 VPS，速度快，性价比高' },
  { logo: '/rfc.png', title: 'RFC Host', link: 'https://aff.dev/rfc', desc: '香港、日本线路好，中国网络优化多' },
  { logo: '/ovh.jpg', title: 'OVH Cloud', link: 'https://aff.dev/ovh', desc: ' 欧洲、加拿大积分，独服巨多' },
  { logo: '/aliyun.png', title: 'Aliyun', link: 'https://aff.dev/aliyun', desc: '国产顶级阿里云，新手适合，客服反馈快' },
  { logo: '/aws.webp', title: 'AWS Lightsail', link: 'https://aff.dev/aws', desc: '个人用很好，3 或者 6 个月免费' },
  { logo: '/oracle.webp', title: 'Oracle Cloud', link: 'https://aff.dev/oracle', desc: '永久免费，开节点看运气' }
]

// 域名注册
const domainList = [
  { logo: '/spaceship.webp', title: 'Spaceship', link: 'https://aff.dev/spaceship', desc: '终身免费 WHOIS 隐私保护 · 支持支付宝' },
  { logo: '/namesilo.webp', title: 'Namesilo', link: 'https://aff.dev/namesilo', desc: '域名优惠多 · 控制台简洁 · DNS 快速' },
  { logo: '/cf.jpg', title: 'Cloudflare', link: 'https://aff.dev/cf', desc: '提供免费域名解析与安全防护' },
  { logo: '/godaddy.webp', title: 'Godaddy', link: 'https://aff.dev/godaddy', desc: '老牌大户注册平台，谁能没有 Daddy' }
]

// 论坛相关
const forumList = [
  { logo: '/let.png', title: 'LowEndTalk', link: 'https://aff.dev/let', desc: '知名国外 VPS 社区，发布优惠与测评' },
  { logo: '/node.jpg', title: 'NodeSeek', link: 'https://aff.dev/node', desc: '中文主机交流区，技术与优惠分享' },
  { logo: '/linuxdo.png', title: 'Linux Do', link: 'https://aff.dev/linux', desc: ' 技术氛围还行，可以问很多问题' },
  { logo: '/v2ex.png', title: 'V2ex', link: 'https://aff.dev/v2ex', desc: '国内第一技术交流论坛，现在吹水巨多' }
]

// 资源汇总
const resourceList = [
  { logo: '/github.webp', title: 'GitHub', link: 'https://aff.dev/git', desc: '开源资源合集，涵盖开发与网络工具' },
  { logo: '/reddit.jpg', title: 'Reddit', link: 'https://aff.dev/reddit', desc: '各种问题都可以问，反响快速有用' },
  { logo: '/speedtest.png', title: 'SpeedTest', link: 'https://aff.dev/speedtest', desc: '测速是唯一的快乐，快测测！' },
  { logo: '/vercel.webp', title: 'Vercel', link: 'https://aff.dev/vercel', desc: '部署必选，和 cf 有一拼，各有优劣' }
]

// 新鲜有趣
const esimList = [
  { logo: '/ryf.jpeg', title: '阮一峰的博客', link: 'https://aff.dev/ryf', desc: '最不像程序员的程序员，文章很好' },
  { logo: '/sspai.png', title: '少数派', link: 'https://aff.dev/sspai', desc: '收集国内外好玩的硬件、项目分享' },
  { logo: '/ph.png', title: 'Product Hunt', link: 'https://aff.dev/ph', desc: '全球最大项目投喂地，可以激发灵感' },
  { logo: '/kickstarter.png', title: 'Kick Starter', link: 'https://aff.dev/kick', desc: '众筹之神，有意思的人都聚集在这里了' }
]
</script>
