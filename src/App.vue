<template>
  <div class="hero is-fullheight-with-navbar" id="app">
    <div class="hero-body">
      <div class="container">
        <div class="columns">
          <div class="column is-two-thirds-desktop">
            <LogoMark />
            <h1 class="title">Angelo Cordon</h1>
            <p class="content">
              I build products that empower people become their best selves. I enjoy merging technical complexities with visual aesthetics to create meaningful user experiences. As a product designer and developer, I value the outcome of my work and strive to make an emotional impact to users.
            </p>
            <MainMessage />
            <MainNavigation />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import LogoMark from './components/LogoMark'
import MainNavigation from './components/MainNavigation'
import MainMessage from './components/MainMessage'

export default {
  name: 'app',
  components: {
    MainNavigation,
    MainMessage,
    LogoMark
  }
}
</script>

<style lang="scss">
  html {
    background-color: #fff;
    padding: 1rem;
  }

  body {
    background-color: #f8f8f8;
    color: #353639;
    font-family: 'Source Serif Pro';
    letter-spacing: 1px;
    line-height: 1.8;
  }

  .title,
  .subtitle { font-family: 'Source Sans Pro' }

  .title { color: #3f58cb }

  .subtitle {
    color: #1f2d6b;
    font-weight: 600;
  }
</style>
