<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>黃金國</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            黃金國是<nuxt-link to="/civs/Mayans">馬雅</nuxt-link
            >的特殊科技，可於<nuxt-link to="/techs/age/Imperial_Age"
              >帝王時代</nuxt-link
            >在
            <nuxt-link to="/building/Castle">城堡</nuxt-link
            >研發。研發後<nuxt-link to="/units/Eagle_Warrior">鷹勇士</nuxt-link
            >HP+40。
          </p>
        </div>
        <h3>戰術要點</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <p>
              乍看之下黃金國給鷹勇士多餘的生命值好像沒有甚麼價值，但一定要研究該技術的優點請看以下描述:
            </p>
            <li>
              馬雅人沒有<nuxt-link to="/units/Knight">騎士</nuxt-link
              >，這大大降低他們前線步兵的生存能力，也讓他們的弓箭手身陷險境。
            </li>
            <li>
              鷹勇士可說是馬雅人的騎兵，而且在一定程度上擔當<nuxt-link
                to="/units/Light_Cavalry"
              ></nuxt-link
              >輕騎兵、<nuxt-link to="/units/Knight">騎士</nuxt-link>、甚至
              <nuxt-link to="/units/Camel">駱駝騎兵</nuxt-link
              >的功能(有遼闊視野，對騎兵有些微攻擊加成)。
            </li>
            <li>
              絕大多數的<nuxt-link to="/units/Infantry_Units"
                >步兵單位</nuxt-link
              >對鷹勇士都有攻擊加成。而且在單挑戰鬥中能相當輕易地擊敗鷹勇士。
            </li>
            <li>
              鷹勇士是馬雅軍隊的核心，但血量不多且很可能面對被某些單位反制，黃金國試著解決這個問題，讓玩家可以有更多空間在戰場上運用鷹勇士做更多事情。
            </li>
          </ul>
        </div>
        <h3>團隊加分</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Berbers">柏柏</nuxt-link>：<nuxt-link
                to="/techs/Kasbah"
                >聚居堡壘</nuxt-link
              >能夠加速黃金國的研究時間(快25%)。
            </li>
          </ul>
        </div>
        <h3>歷史</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <p>
            當明顯不同風情的文化碰撞時這樣的戰爭往往是最殘酷和恐怖的。南美洲和中美洲的土著居民被穿戴著護甲的征服者，揮舞著鋼鐵武器，僱用戰犬和使用槍支鎮壓。
            反過來，美洲人的鮮血犧牲，儀式和狂熱主義使西班牙人感到不安。馬雅人為了保護他們隱藏的財富在激烈的戰鬥中會是非常強硬的對手。
          </p>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">黃金國</div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Unique-tech.jpg" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">
                <nuxt-link to="/techs">科技介紹</nuxt-link>
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4"><nuxt-link to="/civs/Mayans">馬雅</nuxt-link></td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Imperial-age-research.jpg"
                alt=""
              /><nuxt-link to="/techs/age/Imperial_Age">帝王時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">研發於</td>
            <td class="unit4">
              <img class="gg" src="~assets/Castleicon.png" alt="" /><nuxt-link
                to="/building/Castle"
                >城堡</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">研發時間</td>
            <td class="unit4">50秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">食物</td>
            <td class="unit4">750</td>
          </tr>
          <tr>
            <td class="unit3">黃金</td>
            <td class="unit4">450</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">影響</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">影響</td>
            <td class="unit4">鷹勇士 HP+40。</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由賜齡協助編輯</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'alltech',
  components: {}
}
</script>
<style></style>
