<template>
  <div id="p1">
    <div class="c-video-wrapper">
      <iframe class="c-video" width="1280" height="768" src="https://www.youtube.com/embed/lr97zmayoLo?rel=0" frameborder="0" allow="autoplay; encrypted-media"
        allowfullscreen>
      </iframe>
    </div>
    <section>
      <h2>サークル説明会2018</h2>
      <ul class="c-ul">
        <li class="info">4月26日（木）</li>
        <li class="info">4月27日（金）</li>
      </ul>
      <p class="info">K1号館　303教室</p>
      <p class="info">16:40～</p>
    </section>

    <section>
      <h2>サークル連絡先</h2>
      <table border="0" align="center">
        <tr>
          <td width="30%">
            <h3>Twitter</h3>
          </td>
          <td width="70%">
            <a href="https://twitter.com/g_c_circle">twitter@g_c_circle</a>
          </td>
        </tr>
        <tr>
          <td width="30%">
            <h3>Mail</h3>
          </td>
          <td width="70%">
            <a href="mailto:game_sousaku@yahoo.co.jp">kanakou_game@yahoo.co.jp</a>>
          </td>
        </tr>
      </table>
    </section>
    <a class="twitter-timeline" href="https://twitter.com/g_c_circle" data-widget-id="575431985105014784">@g_c_circleさんのツイート</a>
    <script>
      ! function (d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0],
          p = /^http:/.test(d.location) ? 'http' : 'https';
        if (!d.getElementById(id)) {
          js = d.createElement(s);
          js.id = id;
          js.src = p + "://platform.twitter.com/widgets.js";
          fjs.parentNode.insertBefore(js, fjs);
        }
      }(document, "script", "twitter-wjs");

    </script>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        title: 'KAITゲーム創作同好会',
        subtitle: '自作ゲーム配布中',
      }
    },
    asyncData(context) {
      return {
        name: 'トップ'
      }
    }
  }

</script>
