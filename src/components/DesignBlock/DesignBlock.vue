<template>
  <div class="design">
    <div class="design-info">
      <div class="design-info__title">Remote-first. Secure by design.</div>
      <div class="design-info__img">
        <img src="@/assets/design.svg" alt="" />
      </div>
      <div class="design-info__desc">
        You no longer need an over-powered laptop to code, Gitpod works just as
        smoothly on a Chromebook or iPad. All you need is a browser. Gitpod
        centralizes all source code and never stores it on insecure machines and
        networks.
      </div>
    </div>
    <div class="design-nav">
      <li class="design-nav__chrome">
        <a href="/"><img src="@/assets/chrome.svg" alt="" />Chrome Extension</a>
      </li>
      <li class="design-nav__firefox">
        <a href="/"
          ><img src="@/assets/firefox2.svg" alt="" />Firefox Extension</a
        >
      </li>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "@/components/DesignBlock/DesignBlock.scss";
</style>
