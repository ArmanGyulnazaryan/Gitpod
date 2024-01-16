<template>
  <div class="started">
    <div class="started__title">Get started now</div>
    <div class="started-block">
      <div class="started-repository">
        <div class="started-repository__title">Connect Git repository</div>
        <div class="started-repository__desc">
          Select a Git provider to start with an existing project from any Git
          context.
        </div>
        <div class="started-btn">
          <a href="/" class="started-btn__gitlab"
            ><img src="@/assets/started/lab.png" alt="" /><span
              >Continue with GitLab</span
            ></a
          >
          <a href="/" class="started-btn__github"
            ><img src="@/assets/started/hub.png" alt="" /><span
              >Continue with GitHub</span
            ></a
          >
          <a href="/" class="started-btn__bitbucket"
            ><img src="@/assets/started/bitbucket.png" alt="" /><span
              >Continue with BitBucket</span
            ></a
          >
        </div>
        <div class="started-repository__desc">
          Or prefix any GitLab, GitHub or Bitbucket URL with
          <span>gitpod.io/#</span>
        </div>
      </div>
      <div class="started-work">
        <div class="started-work__title">Launch an example workspace</div>
        <div class="started-work__desc">
          Dive into one of our example workspaces
        </div>
        <div class="started-launch">
          <div class="started-wrapper">
            <div class="started-wrapper__img">
              <img src="@/assets/launch/ts.png" alt="ts" />
              <span>Node or TypeScript</span>
            </div>
            <div class="started-wrapper__btn">
              <a href="/">Launch workspace</a>
            </div>
          </div>

          <div class="started-wrapper">
            <div class="started-wrapper__img">
              <img src="@/assets/launch/python.png" alt="python" />
              <span>Python</span>
            </div>
            <div class="started-wrapper__btn">
              <a href="/">Launch workspace</a>
            </div>
          </div>


          <div class="started-wrapper">
            <div class="started-wrapper__img">
              <img src="@/assets/launch/go.png" alt="Go" />
              <span>Go</span>
            </div>
            <div class="started-wrapper__btn">
              <a href="/">Launch workspace</a>
            </div>
          </div>


          <div class="started-wrapper">
            <div class="started-wrapper__img">
              <img src="@/assets/launch/rust.png" alt="Rust" />
              <span>Rust</span>
            </div>
            <div class="started-wrapper__btn">
              <a href="/">Launch workspace</a>
            </div>
          </div>


          <div class="started-wrapper">
            <div class="started-wrapper__img">
              <img src="@/assets/launch/java.png" alt="Java" />
              <span>Java</span>
            </div>
            <div class="started-wrapper__btn">
              <a href="/">Launch workspace</a>
            </div>
          </div>

          <div class="started-wrapper">
            <div class="started-wrapper__img">
              <img src="@/assets/launch/svelte.png" alt="Svelte" />
              <span>Svelte</span>
            </div>
            <div class="started-wrapper__btn">
              <a href="/">Launch workspace</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style lang="scss" scoped>
@import "@/components/StartedBlock/StartedBlock.scss";
</style>
