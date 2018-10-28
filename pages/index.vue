<template>
  <div id="page-wrapper">
    <header-nav />
    <header-banner />

    <article id="main">
      <main-header />
      <main-banner />
      <main-banner-highlights />
      <main-articles />
    </article>

    <footer-banner />
    <footer-nav />

    <script src="/js/jquery.min.js"></script>
    <script src="/js/jquery.dropotron.min.js"></script>
    <script src="/js/jquery.scrolly.min.js"></script>
    <script src="/js/jquery.scrollex.min.js"></script>
    <script src="/js/browser.min.js"></script>
    <script src="/js/breakpoints.min.js"></script>
    <script src="/js/util.js"></script>
    <script src="/js/main.js"></script>
  </div>
</template>

<script>
import HeaderNav from '~/components/HeaderNav.vue'
import HeaderBanner from '~/components/HeaderBanner.vue'
import MainHeader from '~/components/MainHeader.vue'
import MainBanner from '~/components/MainBanner.vue'
import MainBannerHighlights from '~/components/MainBannerHighlights.vue'
import MainArticles from '~/components/MainArticles.vue'
import FooterBanner from '~/components/FooterBanner.vue'
import FooterNav from '~/components/FooterNav.vue'

export default {
  name: 'Home',
  components: {
    HeaderNav,
    HeaderBanner,
    MainHeader,
    MainBanner,
    MainBannerHighlights,
    MainArticles,
    FooterBanner,
    FooterNav
  }
}
</script>
