<template>
  <section class="intro">
    <div class="intro__inner">
      <img class="intro__logo logo" src="/wp-content/themes/hmww/img/profilbild.png"/>
      <div class="intro__content">
        <h1 class="intro__title">Herr Mies will's wissen</h1>

        <section class="intro__text">
          <p>
            <b>
              <i>Herr Mies will's wissen</i>
            </b>
            ist die zweiwöchige Interview-Reihe rund um IT und Entwicklung von und mit Daniel Mies.
          </p>
          <p>
            Du kannst diesen Podcast bequem über die folgende URL abonnieren:
            <a href="https://mies.me/feed/mp3/">https://mies.me/feed/mp3/</a>
          </p>
          <p>
            <a href="https://itunes.apple.com/de/podcast/herr-mies-wills-wissen/id1257454170?mt=2"
               style="display:inline-block;overflow:hidden;background:url(https://linkmaker.itunes.apple.com/assets/shared/badges/de-de/podcast-lrg.svg) no-repeat;width:133px;height:34px;background-size:contain;"></a>
            <a href="https://open.spotify.com/show/0RsiWLsZwLMnB70HpA5hnk?si=vO7eyBAxSHa4Lm1J_sj55Q"><img
                :src="spotifyLogo" width="133" height="34"
                style="display:inline-block"/></a>
          </p>
        </section>
      </div>
    </div>
  </section>
</template>
<script>
  export default {
    data: () => ({
      spotifyLogo: '/wp-content/themes/hmww/dist/'+require('../../img/podcast-badge-spotify.svg')
    })
  }
</script>

<style lang="scss" scoped>
  @import "intro";
</style>
