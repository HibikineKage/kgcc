<template>
  <div>
    <header class="l-header">
      <!--ゲーム創作サークル、トップ画像-->
      <h1 class="l-top-picture">
        <nuxt-link class="l-top-picture__link" to="/">ゲーム創作サークル</nuxt-link>
      </h1>
      <nav class="l-navigation">
        <ul class="l-navigation__ul">
          <li class="l-navigation__li">
            <nuxt-link class="l-navigation__link" to="/">
              トップ
            </nuxt-link>
          </li>
          <li class="l-navigation__li">
            <nuxt-link class="l-navigation__link" to="/activity">
              活動紹介
            </nuxt-link>
          </li>
          <li class="l-navigation__li">
            <nuxt-link class="l-navigation__link" to="/downloads">
              ダウンロード
            </nuxt-link>
          </li>
          <li class="l-navigation__li l-navigation__li--last">
            <nuxt-link class="l-navigation__link" to="/teams">
              チーム
            </nuxt-link>
          </li>
        </ul>
      </nav>
    </header>
    <main class="l-main">
      <nuxt/>
    </main>
  </div>
</template>

<script>
  export default {
    head() {
      return {
        title: 'KAITゲーム創作サークル - ゲーム配布中'
      }
    }
  }

</script>
