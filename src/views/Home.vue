

<template>
  <section class="hero ">
    <div class="flex flex-col gap-4">
      <div class="mt-16 picture flex items-center justify-between sm:flex-col sm:gap-10">
        <div class="flex flex-col gap-4">
          <XyzTransition appear xyz="fade thick-100% duration-15 left-4">
            <h1
              class="text-2xl leading-9 font-extrabold text-gray-900 dark:text-white tracking-tight sm:text-2xl sm:leading-10 md:text-5xl md:leading-14">
              Wellington Henrique
            </h1>
          </XyzTransition>
          <XyzTransition appear xyz="fade thick-100% duration-15 left-4">
            <span class="text-zinc-400  sm:m-auto ">Full-Stack Developer.</span>
          </XyzTransition>
          <XyzTransition appear xyz="fade small-5 thick-100% duration-20 ">
            <div class="social flex items-center w-max gap-3   sm:m-auto ">
              <a title="Instagram" target="_blank" href="https://instagram.com/wellington.henriqueee/">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256" focusable="false" class="w-6 h-6">
                  <g>
                    <path fill="#fff"
                      d="M128,80a48,48,0,1,0,48,48A48.05,48.05,0,0,0,128,80Zm0,80a32,32,0,1,1,32-32A32,32,0,0,1,128,160ZM176,24H80A56.06,56.06,0,0,0,24,80v96a56.06,56.06,0,0,0,56,56h96a56.06,56.06,0,0,0,56-56V80A56.06,56.06,0,0,0,176,24Zm40,152a40,40,0,0,1-40,40H80a40,40,0,0,1-40-40V80A40,40,0,0,1,80,40h96a40,40,0,0,1,40,40ZM192,76a12,12,0,1,1-12-12A12,12,0,0,1,192,76Z">
                    </path>
                  </g>
                </svg>
              </a>
              <a title="Linkedin" target="_blank" href="https://linkedin.com/in/wellington-alfredo/">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256" focusable="false" class="w-6 h-6">
                  <g>
                    <path fill="#fff"
                      d="M216,24H40A16,16,0,0,0,24,40V216a16,16,0,0,0,16,16H216a16,16,0,0,0,16-16V40A16,16,0,0,0,216,24Zm0,192H40V40H216V216ZM96,112v64a8,8,0,0,1-16,0V112a8,8,0,0,1,16,0Zm88,28v36a8,8,0,0,1-16,0V140a20,20,0,0,0-40,0v36a8,8,0,0,1-16,0V112a8,8,0,0,1,15.79-1.78A36,36,0,0,1,184,140ZM100,84A12,12,0,1,1,88,72,12,12,0,0,1,100,84Z">
                    </path>
                  </g>
                </svg>
              </a>
              <a title="Linkedin" target="_blank" href="https://github.com/welldecode/">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="w-6 h-6">
                  <path fill="#fff"
                    d="M12.001 2C6.47598 2 2.00098 6.475 2.00098 12C2.00098 16.425 4.86348 20.1625 8.83848 21.4875C9.33848 21.575 9.52598 21.275 9.52598 21.0125C9.52598 20.775 9.51348 19.9875 9.51348 19.15C7.00098 19.6125 6.35098 18.5375 6.15098 17.975C6.03848 17.6875 5.55098 16.8 5.12598 16.5625C4.77598 16.375 4.27598 15.9125 5.11348 15.9C5.90098 15.8875 6.46348 16.625 6.65098 16.925C7.55098 18.4375 8.98848 18.0125 9.56348 17.75C9.65098 17.1 9.91348 16.6625 10.201 16.4125C7.97598 16.1625 5.65098 15.3 5.65098 11.475C5.65098 10.3875 6.03848 9.4875 6.67598 8.7875C6.57598 8.5375 6.22598 7.5125 6.77598 6.1375C6.77598 6.1375 7.61348 5.875 9.52598 7.1625C10.326 6.9375 11.176 6.825 12.026 6.825C12.876 6.825 13.726 6.9375 14.526 7.1625C16.4385 5.8625 17.276 6.1375 17.276 6.1375C17.826 7.5125 17.476 8.5375 17.376 8.7875C18.0135 9.4875 18.401 10.375 18.401 11.475C18.401 15.3125 16.0635 16.1625 13.8385 16.4125C14.201 16.725 14.5135 17.325 14.5135 18.2625C14.5135 19.6 14.501 20.675 14.501 21.0125C14.501 21.275 14.6885 21.5875 15.1885 21.4875C19.259 20.1133 21.9999 16.2963 22.001 12C22.001 6.475 17.526 2 12.001 2Z">
                  </path>
                </svg>
              </a>
            </div>
          </XyzTransition>
        </div>
        <XyzTransition appear xyz="fade thick-100% duration-10 down-4">
          <figcaption class="w-40 h-40">
            <img src="/image/profiure_picture.jpg" alt="" class="w-full h-full rounded-md shadow-md object-cover">
          </figcaption>
        </XyzTransition>
      </div>
      <XyzTransition appear xyz="fade duration-10 down-4">
        <span class="text-gray-300 font-medium text-base mt-11 text-justify">Olá, me chamo Wellington Henrique, atualmente
          estou
          tentando entrar no mercado de trabalho aplicando conhecimentos que venho aprendendo nos meus estudos e ao longo
          dos anos. Tenho foco com o desenvolvimento web back-end, front-end e ui designer e estou focando em javascript
          para melhorar meus estudos.</span>
      </XyzTransition>
    </div>
    <div class="hidden border border-zinc-800 mt-14"></div>
  </section>
  <section id="cases">
    <div class="content ">
      <div class="title flex flex-col gap-2 max-w-3xl mx-auto px-4 sm:px-6 xl:max-w-5xl xl:px-0  ">
        <XyzTransition appear xyz="fade thick-100% duration-25  ">
          <h1 class="text-slate-100 font-bold text-3xl">Cases da DevStep Studio.</h1>
        </XyzTransition>
        <XyzTransition appear xyz="fade thick-100% duration-15  ">
          <span class="text-gray-400 font-light">Alguns projetos criados pela DevStep Studio.</span>
        </XyzTransition>
      </div>
      <div class="mt-11  ">
        <swiper :slides-per-view="3" :space-between="10">
          <swiper-slide>
            <XyzTransition appear xyz="fade thick-100% duration-5 down-4">
              <article>
                <figure>
                  <img src="/image/cases/case_forflip.svg" alt="" class="w-full h-full">
                </figure>
              </article>
            </XyzTransition>
          </swiper-slide>
          <swiper-slide>
            <XyzTransition appear xyz="fade thick-100% duration-15 down-4">
              <article>
                <figure>
                  <img src="/image/cases/case_archviz.svg" alt="" class="w-full h-full">
                </figure>
              </article>
            </XyzTransition>
          </swiper-slide>
          <swiper-slide>
            <XyzTransition appear xyz="fade thick-100% duration-25 down-4">
              <article>
                <figure>
                  <img src="/image/cases/case_setgo.svg" alt="" class="w-full h-full">
                </figure>
              </article>
            </XyzTransition>
          </swiper-slide>
          <swiper-slide>
            <XyzTransition appear xyz="fade thick-100% duration-30 down-4">
              <article>
                <figure>
                  <img src="/image/cases/case_katabarba.svg" alt="" class="w-full h-full">
                </figure>
              </article>
            </XyzTransition>
          </swiper-slide>
        </swiper>
      </div>
    </div>
  </section>

  <section class="contact hidden" id="contact">
    <div class="title flex flex-col gap-2 max-w-3xl mx-auto px-4 sm:px-6 xl:max-w-5xl xl:px-0  ">
      <XyzTransition appear xyz="fade thick-100% duration-25">
        <h1 class="text-slate-100 font-bold text-3xl">Entre em Contato.</h1>
      </XyzTransition>
      <XyzTransition appear xyz="fade thick-100% duration-15  ">
        <span class="text-gray-400 font-light">Entre em contato comigo para fazer projetos.</span>
      </XyzTransition>
    </div>
  </section>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  data() {
    return { 
      swiperOptions: {
        breakpoints: {
          320: {
            slidesPerView: 1,
            spaceBetween: 10
          },
          770: {
            slidesPerView: 2,
            spaceBetween: 50
          },

          771: {
            slidesPerView: 4,
            spaceBetween: 30
          }
        }
      }
    }
  },

  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);

    };
    const onSlideChange = () => {
      console.log('slide change');
    };
    return {
      onSwiper,
      onSlideChange,
    };
  },
};
</script>