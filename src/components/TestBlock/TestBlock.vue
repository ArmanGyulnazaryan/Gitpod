

  
    
<template>
    <div class="developer">
      <div class="developer__title">Used by 400,000+ developers.</div>
      <div class="developer-info">
        
        <swiper :options="swiperOptions">
          
          <swiper-slide>
            <div class="developer-info__item">
              <div class="developer-info__title">GitPod is incredibly cool.</div>
              <div class="developer-info__desc">
                In my opinion, this is a big step in open source software
                contribution. I'm excited to see where we go from here.
              </div>
    
              <div class="developer-dev">
                <div class="developer-img">
                  <img src="@/assets/man1.svg" alt="man1" />
                </div>
                <div class="developer-dev__name">Ben Halpern</div>
                <div class="developer-dev__prof">
                  Creator and Co-founder <span>@forem</span> and
                </div>
                <div class="developer-dev__email">@ThePracticalDev</div>
              </div>
            </div>
          </swiper-slide>
    
         
          <swiper-slide>
            <div class="developer-info__item">
              <div class="developer-info__title">
                Let's say we were overwhelmed how smooth @gitpod workspaces creation &
                own Docker image for workspaces worked.
              </div>
              <div class="developer-info__desc">
                Plus, installing @code extensions from the store and integrating
                @gitlab CI. That blew my mind entirely, and that is hard ;
              </div>
    
              <div class="developer-dev">
                <div class="developer-dev__img">
                  <img src="@/assets/man2.svg" alt="man2" />
                </div>
                <div class="developer-dev__name">Michael Friedrich</div>
                <div class="developer-dev__prof">
                  Developer Evangelist <span>@GitLab</span>
                </div>
              </div>
            </div>
          </swiper-slide>
    
         
    
        </swiper>
      </div>
    </div>
  </template>
  
  <script>
  import { Swiper, SwiperSlide } from 'vue-awesome-swiper';
  import 'swiper/swiper-bundle.css';
  
  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    data() {
      return {
        swiperOptions: {
          
        },
      };
    },
  };
  </script>
  
  <style lang="scss" scoped>
  @import "@/components/TestBlock/TestBlock.scss";
  </style>