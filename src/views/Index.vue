<template>
  <div>
    <index-navbar />
    <section class="header relative pt-8 items-center flex h-full max-h-960-px">
      <div class="mx-auto items-center flex flex-wrap">
        <div class="md:ml-48">
        </div>
        <div class="w-full md:w-4/12 lg:w-4/12 px-4">
          <div class="pt-32">
            <h1 class="font-semibold text-4xl text-gray-700" style=" font-size:60px">
              <span style="color: #1a73e8">LAY2</span>
            </h1>
            <h3 class="font-semibold text-4xl text-gray-700" style=" font-size:35px">
              Plug <span style="color: #1a73e8;">blockchain</span>
              into the <span style="color: #1a73e8;">Internet</span>
            </h3>
            <p class="mt-4 text-lg leading-relaxed text-gray-600">
              Lay2 Tech is committed to lowering the user barriers of blockchain products,
              creating value with blockchain technology and connecting cryptos with daily life.
            </p>
            <!--
            <div class="mt-12">
              <a href="/" target="_blank"
                class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blue-500 active:bg-indigo-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150">
                Get started
              </a>

              <a href="/"
                class="github-star ml-1 text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-gray-800 active:bg-gray-700 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
                target="_blank">
                Github Star
              </a>
            </div>
            -->
          </div>

        </div>
          <div class="w-full md:w-6/12 lg:w-6/12 pt-32 pl-4">
            <img class="" src="../assets/img/lay2-home-img.png"/>
          </div>

      </div>
<!--
      <img class="absolute b-auto right-16 sm:pt-16 sm:w-4/12 -mt-48 sm:pt-0 max-h-860-px" src="../assets/img/lay2-home-img.png"
        alt="..." />
-->
    </section>

    <section class="mt-48 md:mt-40 pb-40 relative bg-gray-200 pt-64">
      <div class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20" style="transform: translateZ(0);">
        <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none"
          version="1.1" viewBox="0 0 2560 100" x="0" y="0">
          <polygon class="text-gray-200 fill-current" points="2560 0 2560 100 0 100"></polygon>
        </svg>
      </div>
      <div class="container mx-auto mb-12">
        <div class="flex flex-wrap items-center">
          <div class="md:w-6/12 lg:w-6/12 px-6 md:px-4 mr-auto ml-auto -mt-32">
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full rounded-lg bg-gray-200">
              <img alt="..."
                src="../assets/img/lay2-products.png"
                class="w-full align-middle rounded-t-lg" />
            </div>
          </div>

          <div class="w-full md:w-6/12 px-4">
            <div class="flex flex-wrap">
              <div class="relative flex flex-col mt-4">
                <div class="px-4 py-4 flex-auto">
                  <div
                    class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white">
                    <i class="fas fa-code"></i>
                  </div>
                  <h4 class="text-2xl mb-1 font-semibold">
                    PW SDK
                  </h4>
                  <p class="mb-4 text-lg font-light text-gray-600">
                    A friendly and powerful JavaScript / TypeScript SDK for CKB dApps.
                  </p>
                </div>
              </div>
              <div class="relative flex flex-col min-w-0">
                <div class="px-4 py-4 flex-auto">
                  <div
                    class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white">
                    <i class="fas fa-wallet"></i>
                  </div>
                  <h6 class="text-2xl mb-1 font-semibold">
                    Portal Wallet
                  </h6>
                  <p class="mb-4 text-lg font-light text-gray-600">
                    You can receive and send CKB with your Ethereum address in Portal Wallet.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container mx-auto overflow-hidden">
        <div class="flex flex-wrap items-center">
          <div class="w-full md:w-6/12 px-12 md:px-4 ml-auto mr-auto mt-48">
            <div
              class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white">
              <i class="fas fa-code text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal">
              PW SDK
            </h3>
            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-700">
              Every element that you need in developing a CKB dApp comes build in as a component.
              All componets fit perfectly with each other and highly customizable.
            </p>
            <div class="block pb-6">
              <ul>
                <li>
                  <a href="https://github.com/lay2dev/pw-core"
                    class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blue-500 hover:text-blue-800 bg-white uppercase last:mr-0 mr-2 mt-2">
                    PW CORE
                    <i class="fas fa-link"></i>
                  </a>
                  <span class="text-md font-light leading-relaxed text-gray-700">
                    is a front-end JS SDK based on Typescript, which allows developers to directly develop CKB dApps
                    that run in crypto wallets.
                  </span>
                </li>
                <li>
                  <br>
                  <a href="https://github.com/lay2dev/pw-lock"
                    class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blue-500 hover:text-blue-800 bg-white uppercase last:mr-0 mr-2 mt-2">
                    PW LOCK
                    <i class="fas fa-link"></i>
                  </a>
                  <span class="text-md font-light leading-relaxed text-gray-700">
                    is a generic lock script which can verifies signatures from CKB, Bitcoin, Ethereum, EOS and Tron.
                  </span>
                </li>
                <br>
                <li>
                  <a href="https://github.com/lay2dev/libecc"
                    class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blue-500 hover:text-blue-800 bg-white uppercase last:mr-0 mr-2 mt-2">
                    PW LIB
                    <i class="fas fa-link"></i>
                  </a>
                  <span class="text-md font-light leading-relaxed text-gray-700">
                    is a library of cryptographic primitives.
                  </span>
                </li>
              </ul>
            </div>
          </div>

          <div class="md:w-6/12 lg:w-6/12 px-6 md:px-4 mr-auto ml-auto mt-48">
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full rounded-lg bg-gray-200">
              <img alt="..."
                src="../assets/img/pw-sdk.png"
                class="w-full align-middle rounded-t-lg" />
            </div>
          </div>
        </div>

        <div class="flex flex-wrap items-center pt-16">

          <div class="md:w-6/12 lg:w-6/12 px-6 md:px-4 mr-auto ml-auto mt-48">
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full rounded-lg bg-gray-200">
              <img alt="..."
                src="../assets/img/portal-wallet.png"
                class="w-full align-middle rounded-t-lg" />
            </div>
          </div>

          <div class="w-full md:w-6/12 px-12 md:px-4 mr-auto mt-48">
            <div
              class="text-gray-600 p-2 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white">
              <i class="fas fa-wallet text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal">
              Portal Wallet
            </h3>
            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-700">
              In order to create a great User Experience for all users who get use to
              different crypto wallets. You can open and use Portal Wallet in Ethereum browsers.
            </p>
            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-700">
              We will serve all blockchain users with maximum security and convenient.
            </p>
            <a href="https://ckb.pw/" target="_blank"
              class="font-bold text-blue-500 hover:text-blue-800 ease-linear transition-all duration-150">
              Try it now
              <i class="fa fa-angle-double-right ml-1 leading-relaxed"></i>
            </a>
          </div>
        </div>
      </div>

      <div class="container mx-auto px-4 pb-32 pt-48">
        <div class="items-center flex flex-wrap">
          <div class="w-full md:w-6/12 sm:w-12/12 ml-auto px-12 md:px-4">
            <div class="md:pr-12">
              <div
                class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white">
                <i class="fas fa-flask text-xl"></i>
              </div>
              <h3 class="text-3xl font-semibold">
                Experimental Demos
              </h3>
              <p class="mt-4 text-lg font-light leading-relaxed text-gray-600">
                We have developed a lot of cutting-edge and innovative demos and
                we are keeping exploring the endless possibilities of blockchain technology.
                Attention plesae, those demos are experimental and not production ready.
              </p>
              <ul class="list-none mt-6">
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-gray-600 bg-gray-100 mr-3">
                        <i class="fas fa-fingerprint"></i>
                      </span>
                    </div>
                    <div>
                      <a href="https://r1-demo.ckb.pw/" class="font-bold text-blue-500 hover:text-blue-800">
                        WebAuthn Demo
                        <i class="fa fa-angle-double-right ml-1 leading-relaxed"></i>
                      </a>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-gray-600 bg-gray-100 mr-3">
                        <i class="fas fa-hand-holding-usd"></i>
                      </span>
                    </div>
                    <div>
                      <a href="https://pay.lay2.dev/" class="font-bold text-blue-500 hover:text-blue-800">
                        Payment Demo
                        <i class="fa fa-angle-double-right ml-1 leading-relaxed"></i>
                      </a>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>

          <div class="w-full md:w-6/12 mr-auto px-4 pt-24 md:pt-0">
            <img alt="..." class="max-w-full rounded-lg shadow-xl" style="
                transform: scale(1) perspective(1040px) rotateY(-11deg)
                  rotateX(2deg) rotate(2deg);
              " :src="payment" />
          </div>
        </div>
      </div>

      <div class="justify-center text-center flex flex-wrap mt-48 mb-32">
        <div class="w-full md:w-6/12 px-12 md:px-4">
          <h2 class="font-semibold text-4xl">Cooperative Partners</h2>
          <p class="text-lg leading-relaxed mt-4 mb-4 text-gray-600">
            A very big thank you to all our partners for their continued partnership.
          </p>
          <div class="flex mt-24">
            <div class="md:w-3/12 lg:w-3/12 sm:w-6/12 p-2 m-2 bg-white shadow-md rounded-lg text-center">
              <a href="https://www.nervos.org/" target="_blank">
                <img class="max-w-80 mx-auto my-auto mt-1" src="../../src/assets/logo/nervos-new-logo.png" />
              </a>
            </div>
            <div class="md:w-3/12 lg:w-3/12 sm:w-6/12 p-2 m-2 bg-white shadow-md rounded-lg text-center">
              <a href="https://snzholding.com/" target="_blank">
                <img class="max-w-80 mx-auto my-auto mt-1" src="../../src/assets/logo/snz-logo.png" />
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!--
    <section class="block relative z-1 bg-gray-700">
      <div class="container mx-auto">
        <div class="justify-center flex flex-wrap">
          <div class="w-full lg:w-12/12 px-4 -mt-24">
            <div class="flex flex-wrap">
              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Login Page
                </h5>
                <router-link to="/auth/login">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="login"
                    />
                  </div>
                </router-link>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Profile Page
                </h5>
                <router-link to="/profile">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="profile"
                    />
                  </div>
                </router-link>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Landing Page
                </h5>
                <router-link to="/landing">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="landing"
                    />
                  </div>
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    -->

    <section class="py-10 bg-gray-700 overflow-hidden">
      <div class="container mx-auto pb-64">
        <div class="flex flex-wrap justify-center">
          <div class="w-full md:w-8/12 px-12 md:px-4 ml-auto mr-auto md:mt-48">
            <div
              class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white">
              <i class="fas fa-user text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal text-white">
              Join us
            </h3>
            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-200">
              Lay2 Tech is a young blockchain technology company, committed to exploring the
              new field of the combination of blockchain and Internet technology. Hoping to make more
              ordinary people use blockchain technology-based products and applications by constantly
              lowering the use threshold of blockchain products and creating rich blockchain applications and tools.
            </p>
            <p class="text-md font-blod leading-relaxed mt-4 mb-4 text-gray-200">
              Open roles:
            </p>
            <ul>
              <li>
                <a class="font-bold text-white ml-4">
                  <i class="fa fa-hand-point-right ml-1 leading-relaxed"></i> Frontend Engineer (15-30k)
                </a>
              </li>
              <li>
                <a class="font-bold text-white ml-4">
                  <i class="fa fa-hand-point-right ml-1 leading-relaxed"></i> Full Stack Engineer (20-40k)
                </a>
              </li>
            </ul>
            <router-link to="/joinus">
            <a class="mt-8 inline-block text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blue-500 active:bg-indigo-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150">
              know more
            </a>
            </router-link>
          </div>

          <div class="w-full md:w-4/12 px-4 mr-auto ml-auto mt-32 relative">
            <img src="../assets/logo/lay2.png" class="absolute left-auto mt-10">
          </div>
        </div>
      </div>
    </section>

    <section class="pb-16 bg-gray-300 relative pt-32">
      <div class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20" style="transform: translateZ(0);">
        <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none"
          version="1.1" viewBox="0 0 2560 100" x="0" y="0">
          <polygon class="text-gray-300 fill-current" points="2560 0 2560 100 0 100"></polygon>
        </svg>
      </div>

      <div class="container mx-auto">
        <div class="flex flex-wrap justify-center bg-white shadow-xl rounded-lg -mt-64 py-16 px-12 relative z-10">
          <div class="w-full text-center lg:w-8/12">
            <p class="text-4xl text-center">
              <span role="img" aria-label="love">
                😍
              </span>
            </p>
            <h3 class="font-semibold text-3xl">
              Want to keep abreast of our latest news?
            </h3>
            <p class="text-gray-600 text-lg leading-relaxed mt-4 mb-4">
              Cause if you want to, you can just typein your E-mail address below to order our latest news.
              And if you have any problems or advice, or you just want to talk with us, you can send mails to <a
                href="mailto:hello@lay2.dev" style="color: #1a73e8"><u>hello@lay2.dev</u></a>,
              we will respond quitely soon.
            </p>
            <div class="sm:block flex flex-col mt-16">
              <a href="/"
                class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-2 bg-blue-500 active:bg-indigo-600 uppercase text-xl shadow hover:shadow-lg ease-linear transition-all duration-150">
                Submit Now
              </a>
            </div>
            <div class="text-center mt-4"></div>
          </div>
        </div>
      </div>
    </section>
    <footer-component />
  </div>
</template>
<script>
  import IndexNavbar from "@/components/Navbars/IndexNavbar.vue";
  import FooterComponent from "@/components/Footers/Footer.vue";
  import payment from "@/assets/img/payment.png";

  export default {
    data() {
      return {
        payment,
      };
    },
    components: {
      IndexNavbar,
      FooterComponent,
    },
  };
</script>