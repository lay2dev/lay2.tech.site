<template>
  <div>
    <index-navbar />
    <main class="joinus-page">
      <section class="relative block h-500-px">
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style="
            background-image: url('./joinus-banner.png');
          "
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-50 bg-black"
          ></span>
        </div>
        <div
          class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden h-70-px"
          style="transform: translateZ(0);"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon
              class="text-gray-300 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
      </section>

      <section class="relative pt-48 bg-gray-300 pb-48">
        <div class="container mx-auto px-4">
          <div
            class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-xl rounded-lg -mt-64"
          >
            <div class="px-6">
              <div class="flex flex-wrap justify-center">
                <div
                  class="w-full lg:w-3/12 px-4 lg:order-2 flex justify-center"
                >
                  <div class="relative">
                    <img
                      alt="..."
                      src="../assets/img/developers-01.png"
                      class="shadow-xl rounded-full h-auto align-middle border-none absolute -m-16 -ml-20 lg:-ml-16 max-w-150-px bg-white"
                    />
                  </div>
                </div>
                <div
                  class="w-full lg:w-4/12 px-4 lg:order-3 lg:text-right lg:self-center"
                >
                  <div class="pt-24 sm:mt-0">
                  </div>
                </div>
                <div class="w-full lg:w-4/12 px-4 lg:order-1">
                </div>
              </div>
              <div class="text-center mt-8">
                <h3
                  class="text-4xl font-semibold leading-normal mb-2 text-gray-800 mb-2"
                >
                  高级前端工程师
                </h3>
                <div
                  class="text-sm leading-normal mt-0 mb-2 text-gray-500 font-bold uppercase"
                >
                  <i
                    class="fas fa-laugh-wink mr-2 text-lg text-gray-500"
                  ></i>
                  15 ~ 30 k
                </div>
                <div
                  class="text-sm leading-normal mt-0 mb-2 text-gray-500 font-bold uppercase"
                >
                  <i
                    class="fas fa-map-marker-alt mr-2 text-lg text-gray-500"
                  ></i>
                  Hangzhou · China
                </div>

              </div>
              <div class="mt-10 py-10 border-t border-gray-300">
                <div class="flex flex-wrap justify-center">
                  <div class="w-full lg:w-9/12 px-4">
                    <h4 class="text-2xl font-semibold"><i class="fas fa-briefcase mr-4"></i>工作内容</h4>
                     <ul class="mb-4 text-lg leading-relaxed text-gray-800 mt-2">
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 负责相关产品的前端技术方案设计选型
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 为区块链应用开发前端交互页面
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 根据产品需求完成前端的开发、优化和维护工作
                      </li>
                     </ul>

                    <h4 class="text-2xl font-semibold mt-8"><i class="fas fa-code mr-4"></i>任职要求</h4>
                     <ul class="mb-4 text-lg leading-relaxed text-gray-800 mt-2">
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 全日制本科及以上学历，计算机相关专业
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 3 年以上前端开发经验
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 熟练掌握 JavaScript / TypeScript 语言，熟练使用 VUE 框架
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 拥有优秀的工程能力，能独立开发自定义组件，能根据业务发展重构前端架构，熟练使用 Webpack / Babel 或熟悉 Lerna / Yarn workspace 相关的 monorepo 开发模式
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 良好的代码风格和测试习惯，良好的团队协作与沟通能力
                      </li>
                     </ul>

                     <h4 class="text-2xl font-semibold mt-8"><i class="fas fa-gem mr-4"></i>加分项</h4>
                     <ul class="mb-4 text-lg leading-relaxed text-gray-800 mt-2">
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 拥有 PWA 开发经验
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 拥有 dApp 开发经验，包括（ETH、EOS、Tron 等）
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 拥有 TypeScript Library 开发经验
                      </li>
                     </ul>

                     <h4 class="text-2xl font-semibold mt-8"><i class="fas fa-pizza-slice mr-4"></i>福利待遇</h4>
                     <ul class="mb-4 text-lg leading-relaxed text-gray-800 mt-2">
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 五险一金、定期体检、股票期权、带薪年假、公司团建等等
                      </li>
                     </ul>
                  </div>
                </div>
              </div>
              <div class="text-center pt-8 pb-12">
                <button
                    class="bg-blue-500 active:bg-blue-500 uppercase text-white font-bold hover:shadow-lg shadow text-xl px-4 py-2 rounded outline-none focus:outline-none sm:mr-2 mb-1 ease-linear transition-all duration-150"
                    type="button"
                    onClick="window.open('mailto:joinus@lay2.dev')"
                  >
                    Submit Now
                  </button>
              </div>
            </div>
          </div>
        </div>
      </section>

    <section class="relative pt-64 bg-gray-300 pb-48">
        <div class="container mx-auto px-4">
          <div
            class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-xl rounded-lg -mt-64"
          >
            <div class="px-6">
              <div class="flex flex-wrap justify-center">
                <div
                  class="w-full lg:w-3/12 px-4 lg:order-2 flex justify-center"
                >
                  <div class="relative">
                    <img
                      alt="..."
                      src="../assets/img/developers-02.png"
                      class="shadow-lg rounded-full h-auto align-middle border-none absolute -m-16 -ml-20 lg:-ml-16 max-w-150-px bg-white"
                    />
                  </div>
                </div>
                <div
                  class="w-full lg:w-4/12 px-4 lg:order-3 lg:text-right lg:self-center"
                >
                  <div class="pt-24 sm:mt-0">
                  </div>
                </div>
                <div class="w-full lg:w-4/12 px-4 lg:order-1">
                </div>
              </div>
              <div class="text-center mt-8">
                <h3
                  class="text-4xl font-semibold leading-normal mb-2 text-gray-800 mb-2"
                >
                  高级全栈工程师
                </h3>
                <div
                  class="text-sm leading-normal mt-0 mb-2 text-gray-500 font-bold uppercase"
                >
                  <i
                    class="fas fa-laugh-wink mr-2 text-lg text-gray-500"
                  ></i>
                  20 ~ 40 k
                </div>
                <div
                  class="text-sm leading-normal mt-0 mb-2 text-gray-500 font-bold uppercase"
                >
                  <i
                    class="fas fa-map-marker-alt mr-2 text-lg text-gray-500"
                  ></i>
                  Hangzhou · China
                </div>

              </div>
              <div class="mt-10 py-10 border-t border-gray-300">
                <div class="flex flex-wrap justify-center">
                  <div class="w-full lg:w-9/12 px-4">
                    <h4 class="text-2xl font-semibold"><i class="fas fa-briefcase mr-4"></i>工作内容</h4>
                     <ul class="mb-4 text-lg leading-relaxed text-gray-800 mt-2">
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 负责相关产品的前后端技术方案选型
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 根据产品需求完成后端的设计、开发、优化和维护工作
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 根据需求编写相关技术文档
                      </li>
                     </ul>

                    <h4 class="text-2xl font-semibold mt-8"><i class="fas fa-code mr-4"></i>任职要求</h4>
                     <ul class="mb-4 text-lg leading-relaxed text-gray-800 mt-2">
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 全日制本科及以上学历，计算机相关专业
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 3 年以上后端开发经验，1 年以上前端开发经验
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 精通 JavaScript / TypeScript 编程语言，熟练使用 Node 框架构建后端服务，使用 RESTful、GraphQL 等标准与前端对接
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 拥有一定的架构设计能力
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 熟悉 Linux 系统和服务器相关的部署、运维操作
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 良好的代码风格和测试习惯
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 良好的团队协作与沟通能力
                      </li>
                     </ul>

                     <h4 class="text-2xl font-semibold mt-8"><i class="fas fa-gem mr-4"></i>加分项</h4>
                     <ul class="mb-4 text-lg leading-relaxed text-gray-800 mt-2">
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 有区块链相关经验，曾开发过区块链 DApp 者优先
                      </li>
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 有开源项目的经验，开源库维护者优先
                      </li>
                     </ul>

                     <h4 class="text-2xl font-semibold mt-8"><i class="fas fa-pizza-slice mr-4"></i>福利待遇</h4>
                     <ul class="mb-4 text-lg leading-relaxed text-gray-800 mt-2">
                      <li>
                        <i class="fas fa-caret-right mx-4"></i> 五险一金、定期体检、股票期权、带薪年假、公司团建等等
                      </li>
                     </ul>
                  </div>
                </div>
              </div>
              <div class="text-center pt-8 pb-12">
                <button
                    class="bg-blue-500 active:bg-blue-500 uppercase text-white font-bold hover:shadow-lg shadow text-xl px-4 py-2 rounded outline-none focus:outline-none sm:mr-2 mb-1 ease-linear transition-all duration-150"
                    type="button"
                    onClick="window.open('mailto:joinus@lay2.dev')"
                  >
                    Submit Now
                  </button>
              </div>
            </div>
          </div>
        </div>
      </section>

    </main>
    <footer-component />
  </div>
</template>
<script>
 import IndexNavbar from "@/components/Navbars/IndexNavbar.vue";
import FooterComponent from "@/components/Footers/Footer.vue";

import team2 from "@/assets/img/team-2-800x800.jpg";

export default {
  data() {
    return {
      team2,
    };
  },
  components: {
    IndexNavbar,
    FooterComponent,
  },
};
</script>
