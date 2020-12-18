<template>
  <div>
    <index-navbar />
    <main>
      <div
        class="relative pt-16 pb-16 flex content-center items-center justify-center h-800-px"
      >
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style="
            background-image:url('./team-banner.png');
          "
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-50 bg-black "
          ></span>

        </div>
        <div class="container relative mx-auto">
          <div class="items-center flex flex-wrap">
            <div class="w-full lg:w-8/12 px-4 ml-auto mr-auto text-center">
              <div class="pr-6">
                <h1 class="text-white font-semibold text-5xl">
                  Your story starts with Lay2
                </h1>
                <p class="mt-4 text-2xl text-gray-300">
                  We strive for openness, collaboration and are all passionate about decentralized technology and how it can make the world better.
                </p>
              </div>
            </div>
          </div>
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
      </div>

      <section class="pb-20 bg-gray-300 -mt-32 pt-16">
        <div class="container mx-auto px-4">
         <!--
           <div class="flex flex-wrap">
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-400"
                  >
                    <i class="fas fa-award"></i>
                  </div>
                  <h6 class="text-xl font-semibold">Awarded Agency</h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Divide details about your product or agency work into parts.
                    A paragraph describing a feature will be enough.
                  </p>
                </div>
              </div>
            </div>

            <div class="w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-blue-400"
                  >
                    <i class="fas fa-retweet"></i>
                  </div>
                  <h6 class="text-xl font-semibold">Free Revisions</h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Keep you user engaged by providing meaningful information.
                    Remember that by this time, the user is curious.
                  </p>
                </div>
              </div>
            </div>

            <div class="pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-green-400"
                  >
                    <i class="fas fa-fingerprint"></i>
                  </div>
                  <h6 class="text-xl font-semibold">Verified Company</h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Write a few lines about each one. A paragraph describing a
                    feature will be enough. Keep you user engaged!
                  </p>
                </div>
              </div>
            </div>
          </div>
-->
        <section class="pt-48 pb-48">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap justify-center text-center mb-24">
            <div class="w-full lg:w-12/12 px-4">
              <h2 class="text-4xl font-semibold">The Lay2 Team Members</h2>
              <p class="text-lg leading-relaxed m-4 text-gray-600">
                Lay2 Tech is being built by a team of developers and researchers with deep roots in borh the Internet and the crypto sapce.
                The core team members had developed state channel network, lighting network protocols, game payment and so on.
              </p>
            </div>
          </div>
          <div class="flex flex-wrap">
            <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
              <div class="px-6">
                <img
                  alt="..."
                  src="../assets/img/frank3.jpg"
                  class="shadow-lg rounded-full mx-auto max-w-180-px"
                />
                <div class="pt-6 text-center">
                  <h5 class="text-2xl font-bold">Frank Lou</h5>
                  <p class="mt-1 text-md text-gray-500 font-semibold">
                    Chief Executive Officer
                  </p>
                  <div class="mt-6">
                    <button
                      class="bg-blue-400 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://twitter.com/zhixian_lay2')"
                    >
                      <i class="fab fa-twitter"></i>
                    </button>
                    <button
                      class="bg-gray-700 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://github.com/louzhixian')"
                    >
                      <i class="fab fa-github"></i>
                    </button>
                    <button
                      class="bg-blue-600 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://www.linkedin.com/in/louhuanqing/')"
                    >
                      <i class="fab fa-linkedin"></i>
                    </button>

                  </div>
                </div>
              </div>
            </div>
            <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
              <div class="px-6">
                <img
                  alt="..."
                  src="../assets/img/john3.jpg"
                  class="shadow-lg rounded-full mx-auto max-w-180-px"
                />
                <div class="pt-6 text-center">
                  <h5 class="text-2xl font-bold">John Zhang</h5>
                  <p class="mt-1 text-md text-gray-500 font-semibold">
                    Chief Technology Officer
                  </p>
                  <div class="mt-6">
                     <button
                      class="bg-blue-400 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://twitter.com/sking789654')"
                    >
                      <i class="fab fa-twitter"></i>
                    </button>
                     <button
                      class="bg-gray-700 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://github.com/sking789')"
                    >
                      <i class="fab fa-github"></i>
                    </button>
                      <button
                      class="bg-blue-600 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://www.linkedin.com/in/zhang-huaqiang-a4a07a30/')"
                    >
                      <i class="fab fa-linkedin"></i>
                    </button>
                  </div>
                </div>
              </div>
            </div>
            <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
              <div class="px-6">
                <img
                  alt="..."
                  src="../assets/img/jason3.jpg"
                  class="shadow-lg rounded-full mx-auto max-w-180-px"
                />
                <div class="pt-6 text-center">
                  <h5 class="text-2xl font-bold">Jason Cai</h5>
                  <p class="mt-1 text-md text-gray-500 font-semibold">
                    Marketing Director
                  </p>
                  <div class="mt-6">
                    <button
                      class="bg-blue-400 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://twitter.com/JingsongCai')"
                    >
                      <i class="fab fa-twitter"></i>
                    </button>
                    <button
                      class="bg-gray-700 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://github.com/stwith')"
                    >
                      <i class="fab fa-github"></i>
                    </button>
                    <button
                      class="bg-blue-600 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://www.linkedin.com/in/jingsong-cai-b4058715a/')"
                    >
                      <i class="fab fa-linkedin"></i>
                    </button>
                  </div>
                </div>
              </div>
            </div>
            <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
              <div class="px-6">
                <img
                  alt="..."
                  src="../assets/img/kyle3.jpg"
                  class="shadow-lg rounded-full mx-auto max-w-180-px"
                />
                <div class="pt-6 text-center">
                  <h5 class="text-2xl font-bold">Kyle Xu</h5>
                  <p class="mt-1 text-md text-gray-500 font-semibold">
                    Product Researcher
                  </p>
                  <div class="mt-6">
                    <button
                      class="bg-blue-400 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://twitter.com/cnhridol')"
                    >
                      <i class="fab fa-twitter"></i>
                    </button>
                    <button
                      class="bg-gray-700 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      onClick="window.open('https://github.com/kylexyxu')"
                    >
                      <i class="fab fa-github"></i>
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

        </div>
      </section>

      <section class="relative py-20">
        <div
          class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20 h-20"
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
              class="text-white fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>

        <div class="container mx-auto px-4">

          <div class="flex flex-wrap items-center pt-32 pb-64">
            <div class="w-full md:w-6/12 px-4 mr-auto ml-auto">
              <div
                class="text-blue-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-100"
              >
                <i class="fas fa-user-friends text-xl"></i>
              </div>
              <h3 class="text-3xl mb-2 font-semibold leading-normal">
                What we have?
              </h3>
              <p
                class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-700"
              >
                Lay2 is in a period of rapid growth, rapid development, our products and
                ideas are recognized by the core members of the crypto world. We are expecting
                more and more people to join us and grow with us together.
              </p>
              <p
                class="text-lg font-light leading-relaxed mt-0 mb-2 text-gray-700"
              >
                <i class="fas fa-caret-right mx-4 text-gray-700"></i> A united and cooperative team
              </p>
              <p
                class="text-lg font-light leading-relaxed mt-0 mb-2 text-gray-700"
              >
                <i class="fas fa-caret-right mx-4 text-gray-700"></i> Cutting-edge technology and products
              </p>
              <p
                class="text-lg font-light leading-relaxed mt-0 mb-2 text-gray-700"
              >
                <i class="fas fa-caret-right mx-4 text-gray-700"></i> Rich industry resources
              </p>

              <div class="pt-6">
                  <router-link to="/joinus" class="font-bold text-blue-500 hover:text-blue-800">
                  Join us now !
                  <i class="fa fa-angle-double-right ml-1 leading-relaxed"></i>
                </router-link>
                </div>
            </div>

            <div class="w-full md:w-6/12 px-4 mr-auto ml-auto">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6"
              >
                            <img
                alt="..."
                class="max-w-full rounded-lg "
                src="../assets/img/problem-solving.png"
              />

              </div>
            </div>
          </div>

          <div class="items-center flex flex-wrap pb-64">
            <div class="w-full md:w-6/12 ml-auto mr-auto pr-16">
              <img
                alt="..."
                class="max-w-full rounded-lg "
                src="../assets/img/office-room.png"
              />
            </div>
            <div class="w-full md:w-6/12 ml-auto mr-auto px-4">
              <div class="">
                <div
                  class="text-blue-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full"
                >
                  <i class="fas fa-building text-xl"></i>
                </div>
                <h3 class="text-3xl font-semibold">Working with us is a pleasure</h3>
                <p class="mt-4 text-lg font-light leading-relaxed text-gray-600">
                  We are working in a very comfortable environment every day.
                </p>
                <ul class="list-none mt-8">
                  <li class="py-2">
                    <div class="flex items-center">
                      <div>
                        <span
                          class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blue-500 bg-blue-200 mr-3"
                        >
                          <i class="fas fa-coffee"></i>
                        </span>
                      </div>
                      <div>
                        <h4 class="text-gray-600 font-light text-lg ml-2">
                          Comfortable office environment
                        </h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="flex items-center">
                      <div>
                        <span
                          class="text-xs font-semibold inline-block py-1 px-2 rounded-full text-blue-500 bg-blue-200 mr-3"
                        >
                          <i class="fas fa-business-time"></i>
                        </span>
                      </div>
                      <div>
                        <h4 class="text-gray-600 font-light text-lg ml-2">
                          Flexible working
                        </h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="flex items-center ">
                      <div>
                        <span
                          class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blue-500 bg-blue-200 mr-3"
                        >
                          <i class="fas fa-gamepad"></i>
                        </span>
                      </div>
                      <div>
                        <h4 class="text-gray-600 font-light text-lg ml-2">
                          Wealth of activities
                        </h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="flex items-center ">
                      <div>
                        <span
                          class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blue-500 bg-blue-200 mr-3"
                        >
                          <i class="fas fa-biking"></i>
                        </span>
                      </div>
                      <div>
                        <h4 class="text-gray-600 font-light text-lg ml-2">
                          Gym and shower room
                        </h4>
                      </div>
                    </div>
                  </li>
                </ul>
                <div class="pt-8">
                  <router-link to="/joinus" class="font-bold text-blue-500 hover:text-blue-800">
                  Join us now !
                  <i class="fa fa-angle-double-right ml-1 leading-relaxed"></i>
                </router-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
<!--
      <section class="pb-20 relative block bg-gray-900">
        <div
          class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20 h-20"
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
              class="text-gray-900 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>

        <div class="container mx-auto px-4 lg:pt-24 lg:pb-64">
          <div class="flex flex-wrap text-center justify-center">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold text-white">
                Build something
              </h2>
              <p class="text-lg leading-relaxed mt-4 mb-4 text-gray-500">
                Put the potentially record low maximum sea ice extent tihs year
                down to low ice. According to the National Oceanic and
                Atmospheric Administration, Ted, Scambos.
              </p>
            </div>
          </div>
          <div class="flex flex-wrap mt-12 justify-center">
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-medal text-xl"></i>
              </div>
              <h6 class="text-xl mt-5 font-semibold text-white">
                Excelent Services
              </h6>
              <p class="mt-2 mb-4 text-gray-500">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-poll text-xl"></i>
              </div>
              <h5 class="text-xl mt-5 font-semibold text-white">
                Grow your market
              </h5>
              <p class="mt-2 mb-4 text-gray-500">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-lightbulb text-xl"></i>
              </div>
              <h5 class="text-xl mt-5 font-semibold text-white">
                Launch time
              </h5>
              <p class="mt-2 mb-4 text-gray-500">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section class="relative block py-24 lg:pt-0 bg-gray-900">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
            <div class="w-full lg:w-6/12 px-4">
              <div
                class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-300"
              >
                <div class="flex-auto p-5 lg:p-10">
                  <h4 class="text-2xl font-semibold">
                    Want to work with us?
                  </h4>
                  <p class="leading-relaxed mt-1 mb-4 text-gray-600">
                    Complete this form and we will get back to you in 24 hours.
                  </p>
                  <div class="relative w-full mb-3 mt-8">
                    <label
                      class="block uppercase text-gray-700 text-xs font-bold mb-2"
                      htmlFor="full-name"
                    >
                      Full Name
                    </label>
                    <input
                      type="text"
                      class="px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full ease-linear transition-all duration-150"
                      placeholder="Full Name"
                    />
                  </div>

                  <div class="relative w-full mb-3">
                    <label
                      class="block uppercase text-gray-700 text-xs font-bold mb-2"
                      htmlFor="email"
                    >
                      Email
                    </label>
                    <input
                      type="email"
                      class="px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full ease-linear transition-all duration-150"
                      placeholder="Email"
                    />
                  </div>

                  <div class="relative w-full mb-3">
                    <label
                      class="block uppercase text-gray-700 text-xs font-bold mb-2"
                      htmlFor="message"
                    >
                      Message
                    </label>
                    <textarea
                      rows="4"
                      cols="80"
                      class="px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                      placeholder="Type a message..."
                    />
                  </div>
                  <div class="text-center mt-6">
                    <button
                      class="bg-gray-900 text-white active:bg-gray-700 text-sm font-bold uppercase px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150"
                      type="button"
                    >
                      Send Message
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      -->

    </main>
    <footer-component />
  </div>
</template>
<script>
import IndexNavbar from "@/components/Navbars/IndexNavbar.vue";
import FooterComponent from "@/components/Footers/Footer.vue";

export default {
  data() {
    return {
    };
  },
  components: {
    IndexNavbar,
    FooterComponent,
  },
};
</script>
