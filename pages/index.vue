<template>
  <div class="page-index">
    <header class="d-header d-header-home">
      <div class="flex items-center h-full px-1 mx-auto max-w-7xl sm:px-3 lg:px-6">
        <button aria-label="mobileMenu"
                class="flex items-center transition-colors duration-200 justify-center lg:hidden d-icon w-12 h-12 lg:hidden text-gray-300 hover:text-cloud-lighter">
          <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" stroke="currentColor" class="h-6 w-6">
            <path d="M4 6H20M4 12H20M4 18C5.36683 18 6.13317 18 7.5 18C8.86683 18 11 18 11 18" stroke-width="2"
                  stroke-linecap="round" stroke-linejoin="round"></path>
          </svg>
        </button>
        <div class="flex items-center flex-1 justify-center lg:justify-start"><a href="/" aria-label="homeLink"
                                                                                 class="nuxt-link-active">
          <div settings="[object Object]" class="inline-flex items-center space-x-3 h-8 md:h-9">
            <svg viewBox="0 0 221 65" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-8">
              <g clip-path="url(#a)">
                <path fill="currentColor"
                      d="M82.5623 18.5705h7.3017l15.474 24.7415V18.5705h6.741v35.0576h-7.252L89.3025 28.938v24.6901h-6.7402V18.5705ZM142.207 53.628h-6.282v-3.916c-1.429 2.7559-4.339 4.3076-8.015 4.3076-5.822 0-9.603-4.1069-9.603-10.0175V28.3847h6.282v14.3251c0 3.4558 2.146 5.8592 5.362 5.8592 3.524 0 5.974-2.7044 5.974-6.4099V28.3847h6.282V53.628ZM164.064 53.2289l-6.026-8.4144-6.027 8.4144h-6.69l9.296-13.1723-8.58-12.0709h6.843l5.158 7.2641 5.106-7.2641h6.895l-8.632 12.0709 9.295 13.1723h-6.638ZM183.469 20.7726v7.6116h7.149v5.1593h-7.149v12.5311c0 .4208.17.8245.473 1.1223.303.2978.715.4654 1.144.4661h5.532v5.9547h-4.137c-5.617 0-9.293-3.2062-9.293-8.8109V33.5484h-5.056v-5.1642h3.172c1.479 0 2.34-.8639 2.34-2.2932v-5.3184h5.825Z"></path>
                <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M30.1185 11.5456c-1.8853-3.24168-6.5987-3.24169-8.484 0L1.08737 46.8747c-1.885324 3.2417.47133 7.2938 4.24199 7.2938H21.3695c-1.6112-1.4081-2.2079-3.8441-.9886-5.9341l15.5615-26.675-5.8239-10.0138Z"
                      fill="#80EEC0"></path>
                <path
                    d="M43.1374 19.2952c1.5603-2.6523 5.461-2.6523 7.0212 0l17.0045 28.9057c1.5603 2.6522-.39 5.9676-3.5106 5.9676h-34.009c-3.1206 0-5.0709-3.3154-3.5106-5.9676l17.0045-28.9057ZM209.174 53.8005H198.483c0-1.8514.067-3.4526 0-6.0213h10.641c1.868 0 3.353.1001 4.354-.934 1-1.0341 1.501-2.3351 1.501-3.9029 0-1.8347-.667-3.2191-2.002-4.1532-1.301-.9674-2.985-1.4511-5.054-1.4511h-2.601v-5.2539h2.652c1.701 0 3.119-.4003 4.253-1.2009 1.134-.8006 1.701-1.9849 1.701-3.5527 0-1.301-.434-2.3351-1.301-3.1023-.834-.8007-2.001-1.201-3.503-1.201-1.634 0-2.918.4837-3.853 1.4511-.9.9674-1.401 2.1517-1.501 3.5527h-6.254c.133-3.2358 1.251-5.7877 3.352-7.6558 2.135-1.868 4.887-2.8021 8.256-2.8021 2.402 0 4.42.4337 6.055 1.301 1.668.834 2.919 1.9515 3.753 3.3525.867 1.4011 1.301 2.9523 1.301 4.6536 0 1.9681-.551 3.636-1.651 5.0037-1.068 1.3344-2.402 2.235-4.004 2.7021 1.969.4003 3.57 1.3677 4.804 2.9022 1.234 1.5011 1.852 3.4025 1.852 5.7043 0 1.9347-.468 3.7028-1.402 5.304-.934 1.6012-2.301 2.8855-4.103 3.8529-1.768.9674-3.953 1.4511-6.555 1.4511Z"
                    fill="#00DC82"></path>
              </g>
              <defs>
                <clipPath id="a">
                  <path fill="#fff" d="M0 0h221v65H0z"></path>
                </clipPath>
              </defs>
            </svg>
            <span
                class="inline-flex items-center mt-1.2 px-2 py-0.5 rounded text-xs font-medium font-mono bg-cloud-surface dark:bg-sky-dark dark:text-white">RC</span>
          </div>
        </a></div>
        <nav class="items-center hidden h-full lg:flex gap-4"><a href="/getting-started/quick-start"
                                                                 class="font-medium px-2 py-1">
          Getting Started
        </a><a href="/guide/concepts/introduction" class="font-medium px-2 py-1">
          Guide
        </a><a href="/api/composables/use-async-data" class="font-medium px-2 py-1">
          API
        </a><a href="/examples/essentials/hello-world" class="font-medium px-2 py-1">
          Examples
        </a><a href="/community/getting-help" class="font-medium px-2 py-1">
          Community
        </a></nav>
        <div class="flex items-center justify-end gap-1 lg:flex-1"><a href="https://github.com/nuxt/framework"
                                                                      rel="noopener nofollow noreferrer" target="_blank"
                                                                      aria-label="gitHubLink" class="d-icon p-3">
          <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg"
               class="w-6 h-6">
            <path fill-rule="evenodd" clip-rule="evenodd"
                  d="M7.02751 0.333496C3.34571 0.333496 0.333332 3.40836 0.333332 7.16653C0.333332 10.1845 2.23002 12.7468 4.90769 13.6579C5.2424 13.7149 5.35397 13.4871 5.35397 13.3163C5.35397 13.1454 5.35397 12.7468 5.35397 12.1774C3.51307 12.576 3.12257 11.2664 3.12257 11.2664C2.84365 10.4692 2.39737 10.2414 2.39737 10.2414C1.72795 9.8428 2.39737 9.8428 2.39737 9.8428C3.06679 9.89974 3.4015 10.5261 3.4015 10.5261C4.01513 11.5511 4.96347 11.2664 5.35397 11.0955C5.40975 10.64 5.57711 10.3553 5.80024 10.1845C4.29405 10.0136 2.73208 9.44421 2.73208 6.82488C2.73208 6.08463 3.011 5.45827 3.4015 5.00274C3.4015 4.77497 3.12257 4.09166 3.51307 3.18059C3.51307 3.18059 4.07091 3.00977 5.35397 3.8639C5.91181 3.69307 6.46966 3.63613 7.02751 3.63613C7.58536 3.63613 8.14321 3.69307 8.70105 3.8639C9.98411 2.95283 10.542 3.18059 10.542 3.18059C10.9324 4.14861 10.6535 4.83191 10.5977 5.00274C11.044 5.45827 11.2672 6.08463 11.2672 6.82488C11.2672 9.44421 9.70518 10.0136 8.19899 10.1845C8.42213 10.4122 8.64527 10.8108 8.64527 11.4372C8.64527 12.3482 8.64527 13.0885 8.64527 13.3163C8.64527 13.4871 8.75684 13.7149 9.09155 13.6579C11.7692 12.7468 13.6659 10.1845 13.6659 7.16653C13.7217 3.40836 10.7093 0.333496 7.02751 0.333496Z"
                  fill="currentColor"></path>
          </svg>
        </a> <a href="https://twitter.com/nuxt_js" rel="noopener nofollow noreferrer" target="_blank"
                aria-label="twitterLink" class="d-icon p-3 hidden lg:block">
          <svg fill="none" viewBox="0 0 24 24" class="w-6 h-6">
            <path fill-rule="evenodd" clip-rule="evenodd"
                  d="M22 5.897c-.75.33-1.5.577-2.333.66A4.4 4.4 0 0021.5 4.33c-.833.495-1.667.825-2.583.99a4.053 4.053 0 00-3-1.32c-2.25 0-4.084 1.814-4.084 4.041 0 .33 0 .66.084.907-3.5-.165-6.5-1.814-8.5-4.288-.417.66-.584 1.32-.584 2.062 0 1.402.75 2.639 1.834 3.381-.667 0-1.334-.165-1.834-.495v.083c0 1.98 1.417 3.629 3.25 3.958-.333.083-.666.165-1.083.165-.25 0-.5 0-.75-.082.5 1.65 2 2.804 3.833 2.804C6.667 17.608 4.917 18.268 3 18.268c-.333 0-.667 0-1-.082C3.833 19.34 6 20 8.25 20c7.583 0 11.667-6.186 11.667-11.546v-.495c.833-.578 1.5-1.32 2.083-2.062z"
                  fill="currentColor"></path>
          </svg>
        </a>
          <button slot="placeholder" aria-label="Color Mode" class="d-icon hidden lg:block p-3">
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-6 h-6">
              <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M12 2C12.3315 2 12.6495 2.1317 12.8839 2.36612C13.1183 2.60054 13.25 2.91848 13.25 3.25V4.5C13.25 4.83152 13.1183 5.14946 12.8839 5.38388C12.6495 5.6183 12.3315 5.75 12 5.75C11.6685 5.75 11.3505 5.6183 11.1161 5.38388C10.8817 5.14946 10.75 4.83152 10.75 4.5V3.25C10.75 2.91848 10.8817 2.60054 11.1161 2.36612C11.3505 2.1317 11.6685 2 12 2V2ZM17 12C17 13.3261 16.4732 14.5979 15.5355 15.5355C14.5979 16.4732 13.3261 17 12 17C10.6739 17 9.40215 16.4732 8.46447 15.5355C7.52678 14.5979 7 13.3261 7 12C7 10.6739 7.52678 9.40215 8.46447 8.46447C9.40215 7.52678 10.6739 7 12 7C13.3261 7 14.5979 7.52678 15.5355 8.46447C16.4732 9.40215 17 10.6739 17 12V12ZM16.42 18.1875L17.3038 19.0712C17.5395 19.2989 17.8553 19.4249 18.183 19.4221C18.5107 19.4192 18.8243 19.2878 19.056 19.056C19.2878 18.8243 19.4192 18.5107 19.4221 18.183C19.4249 17.8553 19.2989 17.5395 19.0712 17.3038L18.1875 16.42C17.9517 16.1923 17.636 16.0663 17.3082 16.0692C16.9805 16.072 16.667 16.2035 16.4352 16.4352C16.2035 16.667 16.072 16.9805 16.0692 17.3082C16.0663 17.636 16.1923 17.9517 16.42 18.1875V18.1875ZM19.07 4.92875C19.3043 5.16316 19.436 5.48105 19.436 5.8125C19.436 6.14396 19.3043 6.46184 19.07 6.69625L18.1875 7.58C18.0722 7.69939 17.9343 7.79462 17.7818 7.86013C17.6293 7.92564 17.4652 7.96012 17.2993 7.96156C17.1333 7.96301 16.9687 7.93138 16.8151 7.86853C16.6614 7.80568 16.5219 7.71286 16.4045 7.59549C16.2871 7.47813 16.1943 7.33856 16.1315 7.18494C16.0686 7.03132 16.037 6.86672 16.0384 6.70075C16.0399 6.53477 16.0744 6.37075 16.1399 6.21824C16.2054 6.06574 16.3006 5.92781 16.42 5.8125L17.3038 4.92875C17.5382 4.69441 17.856 4.56277 18.1875 4.56277C18.519 4.56277 18.8368 4.69441 19.0712 4.92875H19.07ZM20.75 13.25C21.0815 13.25 21.3995 13.1183 21.6339 12.8839C21.8683 12.6495 22 12.3315 22 12C22 11.6685 21.8683 11.3505 21.6339 11.1161C21.3995 10.8817 21.0815 10.75 20.75 10.75H19.5C19.1685 10.75 18.8505 10.8817 18.6161 11.1161C18.3817 11.3505 18.25 11.6685 18.25 12C18.25 12.3315 18.3817 12.6495 18.6161 12.8839C18.8505 13.1183 19.1685 13.25 19.5 13.25H20.75ZM12 18.25C12.3315 18.25 12.6495 18.3817 12.8839 18.6161C13.1183 18.8505 13.25 19.1685 13.25 19.5V20.75C13.25 21.0815 13.1183 21.3995 12.8839 21.6339C12.6495 21.8683 12.3315 22 12 22C11.6685 22 11.3505 21.8683 11.1161 21.6339C10.8817 21.3995 10.75 21.0815 10.75 20.75V19.5C10.75 19.1685 10.8817 18.8505 11.1161 18.6161C11.3505 18.3817 11.6685 18.25 12 18.25V18.25ZM5.8125 7.58C5.92856 7.69614 6.06635 7.78828 6.21802 7.85116C6.36968 7.91405 6.53225 7.94645 6.69643 7.9465C6.86062 7.94656 7.02321 7.91428 7.17492 7.8515C7.32663 7.78872 7.46449 7.69668 7.58062 7.58062C7.69676 7.46457 7.7889 7.32678 7.85179 7.17511C7.91467 7.02344 7.94707 6.86088 7.94713 6.69669C7.94719 6.53251 7.91491 6.36992 7.85213 6.21821C7.78935 6.0665 7.69731 5.92864 7.58125 5.8125L6.69625 4.92875C6.4605 4.70105 6.14474 4.57506 5.817 4.57791C5.48925 4.58076 5.17574 4.71222 4.94398 4.94398C4.71222 5.17574 4.58076 5.48925 4.57791 5.817C4.57506 6.14474 4.70105 6.4605 4.92875 6.69625L5.8125 7.58V7.58ZM7.58 18.1875L6.69625 19.0712C6.4605 19.2989 6.14474 19.4249 5.817 19.4221C5.48925 19.4192 5.17574 19.2878 4.94398 19.056C4.71222 18.8243 4.58076 18.5107 4.57791 18.183C4.57506 17.8553 4.70105 17.5395 4.92875 17.3038L5.8125 16.42C6.04825 16.1923 6.36401 16.0663 6.69175 16.0692C7.0195 16.072 7.33301 16.2035 7.56477 16.4352C7.79653 16.667 7.92799 16.9805 7.93084 17.3082C7.93369 17.636 7.8077 17.9517 7.58 18.1875V18.1875ZM4.5 13.25C4.83152 13.25 5.14946 13.1183 5.38388 12.8839C5.6183 12.6495 5.75 12.3315 5.75 12C5.75 11.6685 5.6183 11.3505 5.38388 11.1161C5.14946 10.8817 4.83152 10.75 4.5 10.75H3.25C2.91848 10.75 2.60054 10.8817 2.36612 11.1161C2.1317 11.3505 2 11.6685 2 12C2 12.3315 2.1317 12.6495 2.36612 12.8839C2.60054 13.1183 2.91848 13.25 3.25 13.25H4.5Z"
                    fill="currentColor"></path>
            </svg>
          </button>
          <div id="docsearch">
            <button type="button" class="DocSearch DocSearch-Button" aria-label="Search"><span
                class="DocSearch-Button-Container"><svg width="20" height="20" class="DocSearch-Search-Icon"
                                                        viewBox="0 0 20 20"><path
                d="M14.386 14.386l4.0877 4.0877-4.0877-4.0877c-2.9418 2.9419-7.7115 2.9419-10.6533 0-2.9419-2.9418-2.9419-7.7115 0-10.6533 2.9418-2.9419 7.7115-2.9419 10.6533 0 2.9419 2.9418 2.9419 7.7115 0 10.6533z"
                stroke="currentColor" fill="none" fill-rule="evenodd" stroke-linecap="round"
                stroke-linejoin="round"></path></svg></span></button>
          </div>
        </div>
      </div>
    </header>
    <div class="lg:flex"><!---->
      <div class="flex-auto w-full min-w-0 lg:static lg:max-h-full lg:overflow-visible">
        <div class="">
          <div class="overflow-hidden relative dark:bg-sky-black dark:text-white pt-12">
            <div class="flex flex-wrap justify-center py-0 section d-container-content">
              <section
                  class="flex flex-col justify-start w-full px-4 pb-24 sm:pt-12 sm:pb-36 lg:pt-24 lg:pb-50 text-center z-20">
                <div class="highlight-box mx-auto mt-6 rounded-md"><a href="/community/roadmap"
                                                                      class="text-sm inline-flex items-center space-x-1 px-4 md:px-5 py-1 md:py-2 font-medium"><span>Check out the Nuxt 3 roadmap</span>
                  <svg width="1em" height="1em" viewBox="0 0 24 24" class="mt-1px">
                    <path d="M4 11v2h12l-5.5 5.5l1.42 1.42L19.84 12l-7.92-7.92L10.5 5.5L16 11H4z"
                          fill="currentColor"></path>
                  </svg>
                </a></div>
                <canvas class="webgl block m-x-auto"
                        style="opacity: 1; touch-action: none; width: 200px; height: 200px;" data-v-1774a09e=""
                        data-engine="three.js r141" width="200" height="200"></canvas>
                <h1 class="font-normal font-serif text-display-5 xs:text-display-4 md:text-display-3 2xl:text-display-2 mb-6 pt-2">
                  The Hybrid <span class="text-primary">Vue</span> Framework</h1>
                <h2 class="
          font-normal
          text-body-base
          xs:text-body-lg
          md:text-body-xl
          2xl:text-body-2xl
          mb-8
          px-8
          sm:px-0
          dark:text-cloud-lighter
          text-cloud-darker
        ">Build your next application with Vue 3 and experience hybrid rendering, powerful data fetching and new
                  features.
                  Nuxt 3 is an open source framework making web development simple and powerful.</h2>
                <div class="
          flex flex-col
          sm:flex-row
          flex-wrap
          items-center
          justify-center
          space-y-3
          sm:space-y-0 sm:space-x-3
          xl:space-x-4
        "><a href="https://github.com/nuxt/framework" rel="noopener nofollow noreferrer" target="_blank"
             aria-label="Star on GitHub"
             class="font-medium rounded-md dark:bg-sky-black dark:hover:bg-sky-darker hover:bg-cloud-surface inline-flex items-center px-4 py-2.5 text-md 2xl:text-base ">
                  <div class="h-full flex items-center justify-center">
                    <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg"
                         class="mr-2 w-5 h-5">
                      <path fill-rule="evenodd" clip-rule="evenodd"
                            d="M7.02751 0.333496C3.34571 0.333496 0.333332 3.40836 0.333332 7.16653C0.333332 10.1845 2.23002 12.7468 4.90769 13.6579C5.2424 13.7149 5.35397 13.4871 5.35397 13.3163C5.35397 13.1454 5.35397 12.7468 5.35397 12.1774C3.51307 12.576 3.12257 11.2664 3.12257 11.2664C2.84365 10.4692 2.39737 10.2414 2.39737 10.2414C1.72795 9.8428 2.39737 9.8428 2.39737 9.8428C3.06679 9.89974 3.4015 10.5261 3.4015 10.5261C4.01513 11.5511 4.96347 11.2664 5.35397 11.0955C5.40975 10.64 5.57711 10.3553 5.80024 10.1845C4.29405 10.0136 2.73208 9.44421 2.73208 6.82488C2.73208 6.08463 3.011 5.45827 3.4015 5.00274C3.4015 4.77497 3.12257 4.09166 3.51307 3.18059C3.51307 3.18059 4.07091 3.00977 5.35397 3.8639C5.91181 3.69307 6.46966 3.63613 7.02751 3.63613C7.58536 3.63613 8.14321 3.69307 8.70105 3.8639C9.98411 2.95283 10.542 3.18059 10.542 3.18059C10.9324 4.14861 10.6535 4.83191 10.5977 5.00274C11.044 5.45827 11.2672 6.08463 11.2672 6.82488C11.2672 9.44421 9.70518 10.0136 8.19899 10.1845C8.42213 10.4122 8.64527 10.8108 8.64527 11.4372C8.64527 12.3482 8.64527 13.0885 8.64527 13.3163C8.64527 13.4871 8.75684 13.7149 9.09155 13.6579C11.7692 12.7468 13.6659 10.1845 13.6659 7.16653C13.7217 3.40836 10.7093 0.333496 7.02751 0.333496Z"
                            fill="currentColor"></path>
                    </svg>
                  </div>
                  Star on GitHub
                  <!----> </a> <a href="/getting-started/quick-start" aria-label="Get started"
                                  class="button-link medium font-medium" data-v-e8426e6a="">Get started </a></div>
              </section>
            </div>
          </div>
          <div class="relative dark:bg-secondary-darkest bg-gray-50">
            <section class="py-24 md:py-40 text-white light:text-secondary-black">
              <div class="relative w-full d-container-content flex flex-col items-center">
                <div class="flex flex-col w-full items-center col-span-12">
                  <div class="mb-2"><span
                      class="text-cloud-dark dark:text-cloud-light font-bold text-lg">Discover</span></div>
                  <h2 class="font-normal text-center font-serif text-display-6 md:text-display-5 2xl:text-display-4 mb-2">
                    With new features</h2>
                  <p class="font-normal text-center text-body-base md:text-body-lg 2xl:text-body-xl mb-12">Nuxt 3 has
                    been re-architected with a smaller core and optimized for faster performance and better developer
                    experience.</p>
                  <div class="grid grid-cols-1 xs:grid-cols-2 md:grid-cols-3 lg:grid-cols-4">
                    <div to="" aria-label="Lighter"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                           aria-hidden="true" role="img" width="32" height="32" preserveAspectRatio="xMidYMid meet"
                           viewBox="0 0 20 20"
                           class="iconify iconify--entypo mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path
                            d="M4.254 19.567c.307-.982.77-2.364 1.391-4.362c2.707-.429 3.827.341 5.546-2.729c-1.395.427-3.077-.792-2.987-1.321c.091-.528 3.913.381 6.416-3.173c-3.155.696-4.164-.836-3.757-1.067c.939-.534 3.726-.222 5.212-1.669c.766-.745 1.125-2.556.813-3.202c-.374-.781-2.656-1.946-3.914-1.836c-1.258.109-3.231 4.79-3.817 4.754c-.584-.037-.703-2.098.319-4.013c-1.077.477-3.051 1.959-3.67 3.226c-1.153 2.357.108 7.766-.296 7.958c-.405.193-1.766-2.481-2.172-3.694c-.555 1.859-.568 3.721 1.053 6.194c-.611 1.623-.945 3.491-.996 4.441c-.024.759.724.922.859.493z"
                            fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Lighter
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Up to 75x smaller server deployments and smaller client bundle targeting modern browsers.
                      </p></div>
                    <div to="" aria-label="Faster"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                           aria-hidden="true" role="img" width="32" height="32" preserveAspectRatio="xMidYMid meet"
                           viewBox="0 0 28 28"
                           class="iconify iconify--fluent mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <g fill="none">
                          <path
                              d="M18.184 5.55l6.555 6.554a4.305 4.305 0 0 1-4.038 7.234v.246A2.415 2.415 0 0 1 18.286 22H15.5v-.826A3.173 3.173 0 0 0 12.335 18h-1.59a.75.75 0 0 0 0 1.5h1.59c.917 0 1.666.75 1.666 1.674V22H7.399A2.401 2.401 0 0 1 5 19.584v-3.15c0-.233.015-.463.043-.69A2.875 2.875 0 1 1 7.55 11.82c.831-.519 1.814-.82 2.868-.82h4.849c.729 0 1.424.144 2.06.404c.197-.332.438-.615.72-.905l-2.406-2.406a1.798 1.798 0 1 1 2.543-2.543z"
                              fill="currentColor"></path>
                        </g>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Faster
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Optimized cold start with dynamic server code-splitting, powered by nitro.
                      </p></div>
                    <div to="" aria-label="Hybrid"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                           aria-hidden="true" role="img" width="32" height="32" preserveAspectRatio="xMidYMid meet"
                           viewBox="0 0 32 32"
                           class="iconify iconify--carbon mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path d="M17 24.184V20h-2v4.184a3 3 0 1 0 2 0z" fill="currentColor"></path>
                        <path
                            d="M26 12a3.996 3.996 0 0 0-3.858 3H9.858a4 4 0 1 0 0 2h12.284A3.993 3.993 0 1 0 26 12zM6 18a2 2 0 1 1 2-2a2.002 2.002 0 0 1-2 2zm20 0a2 2 0 1 1 2-2a2.002 2.002 0 0 1-2 2z"
                            fill="currentColor"></path>
                        <path d="M19 5a3 3 0 1 0-4 2.816V12h2V7.816A2.992 2.992 0 0 0 19 5z" fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Hybrid
                        <span
                            class="absolute -right-48px inline-flex items-center mt-1px px-1.5 py-0.5 rounded text-xs font-medium font-mono bg-cloud-surface dark:bg-sky-dark dark:text-white">soon</span>
                      </h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Incremental Static Generation and other advanced modes are now possible.
                      </p></div>
                    <div to="" aria-label="Suspense"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                           aria-hidden="true" role="img" width="32" height="32" preserveAspectRatio="xMidYMid meet"
                           viewBox="0 0 32 32"
                           class="iconify iconify--carbon mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path d="M8 16l8-8l8 8l-8 8z" fill="currentColor"></path>
                        <path
                            d="M16 4A12 12 0 1 1 4 16A12.014 12.014 0 0 1 16 4m0-2a14 14 0 1 0 14 14A14 14 0 0 0 16 2z"
                            fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Suspense
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Fetch data in any component, before or after navigation.
                      </p></div>
                    <div to="" aria-label="Composition API"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg width="28" height="25" viewBox="0 0 28 25" fill="none" xmlns="http://www.w3.org/2000/svg"
                           class="mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path
                            d="M11.9467 22.3333C10 25.0933 6.20001 25.7867 3.45334 23.8667C0.720008 21.9467 0.0800078 18.12 2.00001 15.3333C2.53695 14.5538 3.24758 13.9096 4.0759 13.4514C4.90423 12.9933 5.82763 12.7338 6.77334 12.6933L6.84001 14.6C5.62667 14.6933 4.45334 15.32 3.69334 16.4133C2.36001 18.3333 2.77334 20.92 4.60001 22.2133C6.44001 23.4933 9.01334 23 10.3467 21.0933C10.76 20.4933 11 19.84 11.0933 19.1733V17.8267L18.5333 17.7733L18.6267 17.6267C19.3333 16.4 20.8667 15.9733 22.0667 16.6667C22.3539 16.8347 22.6052 17.0577 22.8062 17.3229C23.0072 17.5881 23.154 17.8903 23.2381 18.2122C23.3223 18.5341 23.3423 18.8695 23.2969 19.1991C23.2514 19.5287 23.1415 19.8462 22.9733 20.1333C22.2667 21.3467 20.72 21.7733 19.52 21.08C18.9733 20.7733 18.5867 20.28 18.4133 19.72L12.9867 19.7467C12.8277 20.673 12.4732 21.5548 11.9467 22.3333V22.3333ZM21.6533 12.8133C25.0267 13.2267 27.4267 16.2533 27.0133 19.5733C26.6 22.9067 23.5333 25.2667 20.16 24.8533C19.2232 24.7442 18.3239 24.4219 17.5312 23.9111C16.7384 23.4003 16.0732 22.7146 15.5867 21.9067L17.24 20.9467C17.582 21.4763 18.0365 21.9241 18.5711 22.2582C19.1058 22.5923 19.7074 22.8046 20.3333 22.88C22.6667 23.16 24.7333 21.5733 25.0133 19.3467C25.2933 17.12 23.64 15.08 21.3333 14.8C20.6133 14.72 19.92 14.8133 19.2933 15.04L18.16 15.6267L14.72 9.26667H14.4267C13.7554 9.24713 13.1192 8.96269 12.657 8.47552C12.1948 7.98834 11.9442 7.33803 11.96 6.66667C12 5.28001 13.2 4.20001 14.6 4.25334C16 4.33334 17.1067 5.46667 17.0667 6.85334C17.04 7.44001 16.8133 7.97334 16.4533 8.38667L18.9867 13.0667C19.8133 12.8 20.72 12.7067 21.6533 12.8133V12.8133ZM9.00001 9.18667C7.66667 6.05334 9.08001 2.46667 12.16 1.16001C15.2533 -0.14666 18.8267 1.33334 20.16 4.46667C20.9467 6.29334 20.7867 8.29334 19.8933 9.89334L18.24 8.93334C18.8 7.85334 18.8933 6.53334 18.36 5.29334C17.4533 3.16001 15.04 2.13334 12.9733 3.00001C10.8933 3.88001 9.96001 6.33334 10.8667 8.46667C11.24 9.34667 11.8667 10.0267 12.6267 10.48L13.1467 10.76L9.05334 17.4133C9.09334 17.48 9.14668 17.56 9.18668 17.6667C9.84001 18.88 9.38667 20.4133 8.16001 21.0667C6.94667 21.72 5.41334 21.24 4.74667 19.9867C4.09334 18.7467 4.54667 17.2133 5.77334 16.56C6.29334 16.28 6.86667 16.2133 7.41334 16.3333L10.4933 11.3067C9.86667 10.7333 9.33334 10.0133 9.00001 9.18667V9.18667Z"
                            fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Composition API
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Use the Composition API and Nuxt 3's composables for true code re-usability.
                      </p></div>
                    <div to="" aria-label="Nuxt CLI"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                           aria-hidden="true" role="img" width="32" height="32" preserveAspectRatio="xMidYMid meet"
                           viewBox="0 0 24 24"
                           class="iconify iconify--bx mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path
                            d="M20 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zM6.414 15.707L5 14.293L7.293 12L5 9.707l1.414-1.414L10.121 12l-3.707 3.707zM19 16h-7v-2h7v2z"
                            fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Nuxt CLI
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        A new zero-dependency experience for easy scaffolding and module integration.
                      </p></div>
                    <div to="" aria-label="Nuxt DevTools"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                           aria-hidden="true" role="img" width="32" height="32" preserveAspectRatio="xMidYMid meet"
                           viewBox="0 0 24 24"
                           class="iconify iconify--bx mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path
                            d="M20 3H4c-1.103 0-2 .897-2 2v14c0 1.103.897 2 2 2h16c1.103 0 2-.897 2-2V5c0-1.103-.897-2-2-2zM4 19V7h16l.002 12H4z"
                            fill="currentColor"></path>
                        <path
                            d="M9.293 9.293L5.586 13l3.707 3.707l1.414-1.414L8.414 13l2.293-2.293zm5.414 0l-1.414 1.414L15.586 13l-2.293 2.293l1.414 1.414L18.414 13z"
                            fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Nuxt DevTools
                        <span
                            class="absolute -right-48px inline-flex items-center mt-1px px-1.5 py-0.5 rounded text-xs font-medium font-mono bg-cloud-surface dark:bg-sky-dark dark:text-white">soon</span>
                      </h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Work faster with info and quick fixes right in the browser.
                      </p></div>
                    <div to="" aria-label="Nuxt Kit"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg"
                           class="mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <g clip-path="url(#clip0)">
                          <path
                              d="M3 1.99999L2 2.99999L4.2 6.08099C4.29262 6.21074 4.41491 6.31646 4.55668 6.38934C4.69845 6.46223 4.85559 6.50017 5.015 6.49999H5.085C5.21648 6.49989 5.34669 6.52571 5.46818 6.57599C5.58966 6.62627 5.70004 6.70001 5.793 6.79299L8.468 9.46799L5.851 12.122C5.40339 11.9902 4.93124 11.9646 4.472 12.0471C4.01275 12.1296 3.57905 12.318 3.2053 12.5973C2.83154 12.8766 2.52802 13.2392 2.3188 13.6563C2.10959 14.0733 2.00043 14.5334 2 15C2.0006 15.4299 2.0936 15.8547 2.27271 16.2456C2.45182 16.6364 2.71285 16.9842 3.03811 17.2654C3.36337 17.5466 3.74526 17.7545 4.15792 17.8752C4.57057 17.9959 5.00434 18.0265 5.42985 17.9649C5.85535 17.9033 6.26264 17.7509 6.62413 17.5182C6.98561 17.2854 7.29284 16.9777 7.52501 16.6158C7.75717 16.2539 7.90884 15.8464 7.96975 15.4208C8.03065 14.9952 7.99936 14.5614 7.878 14.149L10.532 11.532L11.5 12.5L11.195 13.414C11.1364 13.5902 11.128 13.7792 11.1707 13.9599C11.2135 14.1405 11.3057 14.3057 11.437 14.437L14.793 17.793C14.9805 17.9805 15.2348 18.0858 15.5 18.0858C15.7652 18.0858 16.0195 17.9805 16.207 17.793L17.793 16.207C17.9805 16.0195 18.0858 15.7652 18.0858 15.5C18.0858 15.2348 17.9805 14.9805 17.793 14.793L14.437 11.437C14.3058 11.3057 14.1405 11.2135 13.9599 11.1707C13.7792 11.128 13.5902 11.1364 13.414 11.195L12.5 11.5L11.54 10.54L14.22 7.89699C14.6646 8.01567 15.1305 8.03066 15.5818 7.9408C16.0331 7.85095 16.4577 7.65866 16.8229 7.37874C17.1882 7.09883 17.4842 6.73878 17.6883 6.32636C17.8924 5.91393 17.999 5.46015 18 4.99999C18 4.73099 17.965 4.46999 17.898 4.22299L15.758 6.36399L14 5.99999L13.636 4.24299L15.777 2.10199C15.2677 1.96505 14.7313 1.9648 14.2219 2.10125C13.7124 2.2377 13.248 2.50604 12.8753 2.87922C12.5026 3.2524 12.2349 3.71723 12.0991 4.22685C11.9634 4.73647 11.9644 5.27287 12.102 5.78199L9.462 8.45999L6.793 5.79299C6.60545 5.6055 6.50006 5.35119 6.5 5.08599V5.01499C6.50002 4.85575 6.462 4.69881 6.38912 4.55723C6.31624 4.41564 6.21061 4.29351 6.081 4.20099L3 1.99999ZM12.646 12.646C12.6924 12.5994 12.7476 12.5625 12.8084 12.5373C12.8691 12.5121 12.9342 12.4991 13 12.4991C13.0658 12.4991 13.1309 12.5121 13.1916 12.5373C13.2524 12.5625 13.3076 12.5994 13.354 12.646L16.354 15.646C16.4005 15.6925 16.4374 15.7477 16.4625 15.8084C16.4877 15.8691 16.5006 15.9342 16.5006 16C16.5006 16.0657 16.4877 16.1308 16.4625 16.1916C16.4374 16.2523 16.4005 16.3075 16.354 16.354C16.3075 16.4005 16.2523 16.4374 16.1916 16.4625C16.1308 16.4877 16.0657 16.5006 16 16.5006C15.9343 16.5006 15.8692 16.4877 15.8084 16.4625C15.7477 16.4374 15.6925 16.4005 15.646 16.354L12.646 13.354C12.5994 13.3075 12.5625 13.2524 12.5373 13.1916C12.5121 13.1309 12.4991 13.0658 12.4991 13C12.4991 12.9342 12.5121 12.8691 12.5373 12.8084C12.5625 12.7476 12.5994 12.6924 12.646 12.646ZM5 13L5.471 13.242L6 13.268L6.287 13.713L6.732 14L6.758 14.529L7 15L6.758 15.471L6.732 16L6.287 16.287L6 16.732L5.471 16.758L5 17L4.529 16.758L4 16.732L3.713 16.287L3.268 16L3.242 15.471L3 15L3.242 14.529L3.268 14L3.713 13.713L4 13.268L4.529 13.242L5 13Z"
                              fill="currentColor"></path>
                        </g>
                        <defs>
                          <clipPath id="clip0">
                            <rect width="16" height="16" fill="white" transform="translate(2 2)"></rect>
                          </clipPath>
                        </defs>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Nuxt Kit
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Brand new module development with TypeScript and cross-version compatibility.
                      </p></div>
                    <div to="" aria-label="Webpack 5"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                           aria-hidden="true" role="img" width="32" height="32" preserveAspectRatio="xMidYMid meet"
                           viewBox="0 0 32 32"
                           class="iconify iconify--cib mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path
                            d="M28.021 24.161l-11.552 6.505v-5.068l7.198-3.943zm.792-.713V9.839l-4.229 2.432v8.745zm-24.912.713l11.552 6.505v-5.068l-7.198-3.943zm-.792-.713V9.839l4.229 2.432v8.745zm.495-14.49l11.849-6.672v4.901l-7.646 4.188zm24.714 0L16.469 2.286v4.901l7.646 4.188zm-12.865 15.49l-7.099-3.891v-7.703l7.099 4.083zm1.016 0l7.099-3.891v-7.703l-7.099 4.083zM8.833 11.964l7.13-3.901l7.13 3.901l-7.13 4.099z"
                            fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Webpack 5
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Faster build time and smaller bundle size, with no configuration required.
                      </p></div>
                    <div to="" aria-label="Vite"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg"
                           class="mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path fill-rule="evenodd" clip-rule="evenodd"
                              d="M15.29 8.384l-.547 9.368a.436.436 0 00.53.455l3.29-.77a.437.437 0 01.522.516l-.977 4.856a.436.436 0 00.55.51l2.032-.627a.436.436 0 01.551.51l-1.553 7.628c-.097.478.529.738.79.329l.173-.274 9.627-19.495c.16-.327-.117-.7-.47-.63l-3.386.663a.438.438 0 01-.499-.554l.799-2.81 9.253-1.712c.721-.133 1.27.646.912 1.296l-15.963 28.97a.861.861 0 01-1.51.006L3.133 7.646c-.365-.648.182-1.434.906-1.303l11.25 2.04z"
                              fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Vite
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Experience lightning fast HMR by using Vite as your bundler.
                      </p></div>
                    <div to="" aria-label="Vue 3"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg width="26" height="26" viewBox="0 0 26 26" fill="none" xmlns="http://www.w3.org/2000/svg"
                           class="mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path d="M0 2L13 24L26 2H16L13 7.3L10 2H0ZM3.5 4H7.271L13 14L18.729 4H22.5L13 20.1L3.5 4Z"
                              fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        Vue 3
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Vue 3 is a solid foundation for your next web app.
                      </p></div>
                    <div to="" aria-label="TypeScript"
                         class="flex flex-col items-center transition duration-200 p-6 rounded-md">
                      <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg"
                           class="mb-4 transition duration-200 text-primary group-hover:text-primary-400 w-10 h-10">
                        <path fill-rule="evenodd" clip-rule="evenodd"
                              d="M4.71 1h30.58C37.338 1 39 2.661 39 4.71v30.58A3.71 3.71 0 0135.29 39H4.71A3.711 3.711 0 011 35.29V4.71C1 2.662 2.662 1 4.71 1zm19.817 30.354v-.147l-.14.033c.046.039.093.077.14.114zm0 0v3.564c.602.312 1.336.542 2.153.698.816.156 1.707.23 2.597.23.891 0 1.707-.082 2.524-.253a6.398 6.398 0 002.078-.816c.601-.393 1.113-.89 1.41-1.559.297-.668.527-1.41.527-2.375 0-.675-.104-1.261-.304-1.78-.2-.52-.49-.966-.89-1.337a5.902 5.902 0 00-1.337-1.039 16.568 16.568 0 00-1.781-.89c-.304-.125-.573-.246-.84-.366a38.461 38.461 0 00-.496-.22c-.386-.194-.72-.387-.965-.58a2.65 2.65 0 01-.63-.623 1.303 1.303 0 01-.223-.742c0-.253.066-.483.2-.69.134-.208.32-.38.557-.528.237-.148.534-.26.89-.341a5.186 5.186 0 011.188-.119c.311 0 .638.023.965.07a8.255 8.255 0 012.078.579c.326.148.63.32.89.512v-3.488a9.16 9.16 0 00-1.855-.483 14.867 14.867 0 00-2.3-.155c-.892 0-1.708.096-2.524.282a5.876 5.876 0 00-2.079.89c-.6.4-1.039.89-1.41 1.559-.348.623-.52 1.336-.52 2.226 0 1.114.32 2.078.966 2.82.638.817 1.633 1.41 2.894 2.005.443.18.841.359 1.229.534l.181.082c.446.2.817.408 1.114.623.319.215.571.453.742.705.185.253.282.55.282.89a1.385 1.385 0 01-.17.668 1.46 1.46 0 01-.528.535 3.012 3.012 0 01-.89.356 5.43 5.43 0 01-1.262.126 6.729 6.729 0 01-2.375-.423 7.036 7.036 0 01-2.086-1.147zm-1.484-9.276h-4.75V35.66h-3.785V22.078h-4.75v-3.043h13.285v3.043z"
                              fill="currentColor"></path>
                      </svg>
                      <h3 class="relative inline-flex mb-1 text-center text-body-lg items-center lg:text-body-xl font-bold">
                        TypeScript
                        <!----></h3>
                      <p class="text-center text-sm lg:text-base mb-4">
                        Built with native TypeScript and ESM - no extra steps required.
                      </p></div>
                  </div>
                  <a href="/getting-started" aria-label="Get started" class="button-link medium font-medium"
                     data-v-e8426e6a="">Get started </a></div>
              </div>
            </section>
          </div>
          <section class="py-20 text-lg">
            <div class="relative w-full d-container-content text-justify">
              <svg viewBox="0 0 450 325" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-32">
                <path
                    d="M293.063 10.056c56.455 7.127 145.001 79.138 140.169 192.691M293.063 16.666c52.999 6.827 136.412 77.692 131.798 181.466M291.992 23.152c49.096 6.552 126.443 69.359 124.458 172.627"
                    stroke="#00DC82" stroke-width="2"></path>
                <circle cx="248.964" cy="180.002" r="143.734" stroke="#00DC82" stroke-width="2"></circle>
                <circle cx="248.964" cy="177.258" r="37.599" stroke="#00DC82" stroke-width="3"></circle>
                <path
                    d="M273.682 117.498l-2.035 5.311c21.301 8.989 36.549 29.953 36.937 54.434h5.684c-.39-26.902-17.152-49.935-40.586-59.745z"
                    fill="#00DC82"></path>
                <path
                    d="M281.544 95.64l-2.825 7.577c29.555 12.213 50.873 40.764 51.412 74.023h7.885c-.541-36.549-23.957-68.272-56.472-81.6z"
                    fill="#00DC82"></path>
                <path
                    d="M291.548 67.793l-3.809 9.736c39.878 16.478 68.023 54.835 68.75 99.712h10.64c-.73-49.317-31.708-91.464-75.581-109.448z"
                    fill="#00DC82"></path>
                <circle cx="248.964" cy="177.259" r="18.392" stroke="#00DC82" stroke-width="3"></circle>
                <circle cx="142.228" cy="199.905" r="14.94" stroke="#00DC82" stroke-width="2"></circle>
                <circle cx="225.106" cy="281.648" r="14.94" stroke="#00DC82" stroke-width="2"></circle>
                <circle cx="181.709" cy="194.289" r="9.324" stroke="#00DC82" stroke-width="2"></circle>
                <circle cx="189.858" cy="235.991" r="13.631" stroke="#00DC82" stroke-width="2"></circle>
                <circle cx="248.279" cy="180.688" r="130.201" stroke="#00DC82" stroke-width="3"></circle>
                <path
                    d="M401.929 282.208c24.245 0 43.9-19.655 43.9-43.901 0-24.245-19.655-43.9-43.9-43.9-3.93 0-6.503.423-10.127 1.391l-.297-4.175c3.734-.931 6.402-1.331 10.424-1.331 26.518 0 48.016 21.497 48.016 48.015 0 26.519-21.498 48.016-48.016 48.016-16.015 0-30.199-7.84-38.922-19.892l2.62-3.43c7.902 11.594 21.213 19.207 36.302 19.207z"
                    fill="#00DC82"></path>
                <path
                    d="M401.929 272.605c19.767 0 35.669-15.73 35.669-34.983 0-19.254-15.902-34.983-35.669-34.983-4.343 0-7.588.52-11.433 1.911v-4.348c3.887-1.245 7.123-1.679 11.433-1.679 21.973 0 39.785 17.505 39.785 39.099 0 21.593-17.812 39.098-39.785 39.098-14.139 0-26.555-7.248-33.611-18.17l2.744-3.391c6.163 10.414 17.651 17.446 30.867 17.446z"
                    fill="#00DC82"></path>
                <path
                    d="M401.929 263.002c13.638 0 24.694-11.056 24.694-24.694s-11.056-24.694-24.694-24.694c-5.881 0-10.474 2.055-14.715 5.487l.674-5.487c4.336-2.613 8.609-4.116 14.041-4.116 15.911 0 28.809 12.899 28.809 28.81s-12.898 28.809-28.809 28.809c-13.051 0-23.827-6.597-27.369-18.497l3.264-4.116c1.959 11.679 11.869 18.498 24.105 18.498z"
                    fill="#00DC82"></path>
                <path d="M108.631 149.881H75.365V69.547c0-37.555 30.444-68 68-68h138.164v38.65" stroke="#00DC82"
                      stroke-width="3"></path>
                <path stroke="#00DC82" stroke-width="2"
                      d="M283.49 7.708h8.811v17.943h-8.811zM48.44 102.206h25.925v28.717H48.44zM48.838 107.08H2.796M48.838 116.868H2.796M48.838 126.392H2.796M115.194 232.746H58.853l-17.877 18.449v52.009h133.781"></path>
                <path
                    d="M41.282 298.48L9.887 283.065l3.611-8.802 27.784 13.013M40.976 272.848l-30.243-14.67 3.61-8.802 26.633 12.639M8.43 242.485l7.372 3.24-6.935 15.778-7.371-3.24zM8.631 268.316l6.142 2.473L8.648 286l-6.142-2.473zM253.637 297.644v-63.268c34.998-2.159 54.249-25.026 54.249-51.609h58.098c-14.301 95.667-83.405 116.731-112.347 114.877zM137.434 176.212h58.716c2.215-32.526 25.277-50.39 52.061-50.356v-58.35c-80.088 0-110.777 74.058-110.777 108.706zM148.271 176.579c3.346-36.424 34.406-98.159 100.169-98.159M162.333 176.597c2.876-31.305 29.57-84.362 86.09-84.362M178.238 176.617c2.344-25.514 24.101-68.757 70.165-68.757M264.06 233.927v63.561M276.397 230.031v65.127M288.063 222.684v68.544M300.951 208.125v78.11M314.2 182.767v95.294M314.482 196.151h48.525M314.267 210.912h45.076M313.969 226.273h39.435M314.484 241.378l31.981.055M314.481 255.77l21.778-.028M313.804 268.183h11.119M141.187 185.053l40.49-.061M190.008 190.066l46.787 82.304M131.048 209.839l81.679 80.139"
                    stroke="#00DC82" stroke-width="2"></path>
              </svg>
              <h1 class="font-normal font-serif text-display-5 xs:text-display-4 md:text-display-3 2xl:text-display-2 my-4">
                Nitro Engine</h1>
              <p data-v-bcba96ca="">We worked for 9 months on Nuxt's new server engine for Nuxt: <a
                  href="/guide/concepts/server-engine" data-v-53a84f30="" class="" data-v-bcba96ca=""><strong
                  data-v-7c7b61be="">Nitro</strong> </a>. It unlocks new <strong data-v-7c7b61be="" data-v-bcba96ca="">full-stack
                capabilities</strong> to Nuxt server and beyond.</p>
              <p data-v-bcba96ca="">In development, it uses <a href="https://rollupjs.org/guide/en/"
                                                               rel="nofollow noopener noreferrer" data-v-53a84f30=""
                                                               data-v-bcba96ca="">Rollup </a> and <a
                  href="https://nodejs.org/api/worker_threads.html" rel="nofollow noopener noreferrer"
                  data-v-53a84f30="" data-v-bcba96ca="">Node.js workers </a> for your server code and context isolation.
                It also <strong data-v-7c7b61be="" data-v-bcba96ca="">generates your server API</strong> by reading
                files in <a href="/guide/directory-structure/server#api-routes" data-v-53a84f30="" class=""
                            data-v-bcba96ca=""><code data-v-10acb923="">server/api/</code> </a> and <strong
                    data-v-7c7b61be="" data-v-bcba96ca="">server middleware</strong> from <a
                    href="/guide/directory-structure/server#server-middleware" data-v-53a84f30="" class=""
                    data-v-bcba96ca=""><code data-v-10acb923="">server/middleware/</code> </a>.</p>
              <p data-v-bcba96ca="">In production, it builds your app and server into one universal <a
                  href="/guide/directory-structure/output" data-v-53a84f30="" class="" data-v-bcba96ca=""><code
                  data-v-10acb923="">.output</code> </a> directory. This <strong data-v-7c7b61be="" data-v-bcba96ca="">output
                is light</strong>: minified and removed from any Node.js modules (except polyfills). You can deploy this
                output on any system supporting JavaScript, from Node.js, Serverless, Workers, Edge-side rendering or
                purely static.</p>
              <p data-v-bcba96ca="">The output is combined with both runtime code to run your Nuxt server in any
                environment (including experimental browser Service Workers!) and serve you static files, making it a
                <strong data-v-7c7b61be="" data-v-bcba96ca="">true hybrid framework</strong> for the JAMStack. In
                addition, a native storage layer is implemented, supporting multi source, drivers and local assets.</p>
              <p data-v-bcba96ca="">The foundation of the Nitro server is rollup and <a
                  href="https://github.com/unjs/h3" rel="nofollow noopener noreferrer" data-v-53a84f30=""
                  data-v-bcba96ca="">h3 </a>: a minimal http framework built for high performance and portability.</p><a
                href="/guide/concepts/server-engine" aria-label="Learn more about Nitro"
                class="button-link medium font-medium" data-v-e8426e6a="">Learn more about Nitro </a></div>
          </section>
          <section class="dark:bg-secondary-darkest bg-gray-50 py-20 text-justify">
            <div class="relative w-full d-container-content text-justify">
              <svg viewBox="0 0 568 289" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-32">
                <path
                    d="M105.365 183.284C161.654 157.422 219.244 64.129 227.008 7.046M181.669 1.788C177.258 33.024 83.023 133.863.76 177.934M189.542 2.732c61.84 114.358 214.646 306.74 347.993 141.883M231.098 1.304c23.17 105.268 181.771 292.873 290.458 139.889M541.033 136.009c1.939 27.604 6.824 90.458 25.987 97.575M132.872 72.038v119.676M139.04 65.938v125.776M253.581 59.892V197.26M258.992 69.637l.842 128.066M289.779 114.709v90.618M295.385 121.554l-.003 84.341M319.711 147.263v61.886M325.301 152.285l.723 57.28M352.124 173.609v43.94M358.424 177.317l.003 40.897M382.042 189.402v29.78M387.559 191.789l.784 27.827M414.444 199.134v21.416M420.23 199.346l.001 21.897M439.916 198.501v22.05M445.701 197.202v24.041M463.16 192.107v29.031M468.945 189.609v32.448M486.444 178.489v43.352M492.229 174.023l-.002 48.856M504.637 161.891v63.006M510.445 155.54v71.24M548.386 196.564v35.017M554.195 216.899l-.005 16.564M165.132 33.843v157.876M171.291 24.5l-.002 167.223"
                    stroke="#00DC82" stroke-width="2"></path>
                <path d="M189.156 1.338l4.584-.395v286.53l-4.584 1.516V1.338z" fill="#40E5A1"></path>
                <path fill="#00DC82"
                      d="M184.938 26.536h38.323v8.822h-38.323zM182.97 59.135h38.323v8.822H182.97zM182.97 91.733h38.323v8.822H182.97zM184.938 124.333h38.323v8.822h-38.323z"></path>
                <path
                    d="M227.479 1.336l4.585-.394V287.47l-4.585 1.516V1.337zM522.195 136.145l2.643-.206v127.914l-2.642 1.05-.001-128.758z"
                    fill="#40E5A1"></path>
                <path fill="#00DC82"
                      d="M520.303 140.366h17.191v4.186h-17.191zM519.42 155.834h17.191v4.186H519.42zM519.42 171.304h17.191v4.186H519.42zM520.303 186.772h17.191v4.186h-17.191z"></path>
                <path d="M539.386 136.142l2.643-.206V263.85l-2.643 1.056V136.142z" fill="#40E5A1"></path>
                <path
                    d="M567.372 238.089C444.413 215.892.278 215.177.278 215.177v-38.119c110.66-3.113 458.828 38.476 567.094 55.602v5.429z"
                    fill="#00DC82"></path>
                <path d="M518.911 136.595l.317-.032-.317.099v-.067zM536.102 136.592l.317-.032-.317.099v-.067z"
                      stroke="#00E889"></path>
                <path fill="#00DC82"
                      d="M180.719 1.338h8.438v287.651h-8.438zM219.042 1.338h8.438v287.651h-8.438zM518.411 136.146h3.785v128.758h-3.785zM535.602 136.146h3.785v128.758h-3.785z"></path>
              </svg>
              <h1 class="font-normal font-serif text-display-5 xs:text-display-4 md:text-display-3 2xl:text-display-2 my-4">
                Nuxt Bridge</h1>
              <p data-v-bcba96ca="">We moved to <a href="https://vuejs.org/" rel="nofollow noopener noreferrer"
                                                   data-v-53a84f30="" data-v-bcba96ca="">Vue 3 </a> and re-wrote Nuxt
                after 4 years of development to make it a strong foundation for the future.</p>
              <h3 id="smooth-upgrade-to-nuxt-3" data-v-34b71bd1=""><a href="#smooth-upgrade-to-nuxt-3"
                                                                      rel="noopener nofollow noreferrer"
                                                                      data-v-53a84f30="" data-v-34b71bd1="">Smooth
                upgrade to Nuxt 3 </a></h3>
              <p data-v-bcba96ca="">We've worked to make the upgrade as easy as possible between Nuxt 2 and Nuxt 3.</p>
              <div>
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Legacy plugins and modules will keep working
</span></div>
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Nuxt 2 config is compatible
</span></div>
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Partial pages options API available
</span></div>
              </div>
              <h3 id="bringing-nuxt-3-experience-to-your-existing-nuxt-2-project" data-v-34b71bd1=""><a
                  href="#bringing-nuxt-3-experience-to-your-existing-nuxt-2-project" rel="noopener nofollow noreferrer"
                  data-v-53a84f30="" data-v-34b71bd1="">Bringing Nuxt 3 experience to your existing Nuxt 2 project </a>
              </h3>
              <p data-v-bcba96ca="">As we've been working on new features for Nuxt 3, we've back-ported some of them to
                Nuxt 2.</p>
              <div class="mb-8">
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Using <a href="/guide/concepts/server-engine" data-v-53a84f30="" class="">Nitro server </a> with Nuxt 2
</span></div>
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Using Composition API (same as Nuxt 3) with Nuxt 2
</span></div>
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Using new CLI and DevTools with Nuxt 2
</span></div>
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Progressively upgrade to Nuxt 3
</span></div>
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Compatibility with Nuxt 2 module ecosystem
</span></div>
                <div class="mt-3 flex items-center"><span class="mt-px mr-3 flex-shrink-0 list-primary"><svg fill="none"
                                                                                                             stroke-linecap="round"
                                                                                                             stroke-linejoin="round"
                                                                                                             stroke-width="2"
                                                                                                             viewBox="0 0 24 24"
                                                                                                             stroke="currentColor"
                                                                                                             class="h-6 w-6"><path
                    d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path></svg></span>
                  <span>
Upgrade piece by piece (Nitro, Composition API, Nuxt Kit)
</span></div>
              </div>
              <a href="/bridge" aria-label="Get started" class="button-link medium font-medium" data-v-e8426e6a="">Get
                started with Nuxt Bridge </a></div>
          </section>
        </div>
      </div>
    </div>
    <Logos/>
    <TestLogos/>
    <Examples/>
    <NuxtLogo/>
  </div>
</template>

<style>
</style>
<script>
import NuxtLogo from "../components/NuxtLogo";

export default {
  components: {NuxtLogo}
}
</script>
