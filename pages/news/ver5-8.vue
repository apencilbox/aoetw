<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>HD Patch 5.8改版資訊</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-12">
        <div class="n1">
          <p>
            5.8改版於2018年9月7日正式上線，除了一些遊戲優化外，還大幅修正了一些遊戲平衡，把韓國和塔攻都削弱了不少，飛鏢騎兵與鷹勇士再度被弱化。
            <a
              href="https://steamcommunity.com/app/221380/discussions/1/1743342466037998931/"
              >原文</a
            >
          </p>
          <p>
            <a href="https://forum.gamer.com.tw/C.php?bsn=1122&snA=14418&tnum=1"
              >資料來源</a
            >並參考PTT Lanchi與<a
              href="http://www.hawkaoe.net/bbs/forum.php?mod=viewthread&tid=143802"
              >翔鷹論壇</a
            >的翻譯
          </p>
        </div>
        <h3>改版內容</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <h4><strong>單位平衡</strong></h4>
          削弱
          <ul>
            <li>
              <img
                src="~assets/EagleScoutIcon.jpg"
                class="gg"
                alt=""
              />鷹斥候在城堡時代生產時間從32s → 35s(跟鷹勇士一樣了)
            </li>
            <li>
              <img
                src="~assets/Watchtowericon.png"
                class="gg"
                alt=""
              />箭塔花費25W 125S → 50W 125S
            </li>
            <li>
              <img
                src="~assets/Arambaiicon.png"
                class="gg"
                alt=""
              />飛鏢騎兵花費55W 60G → 80W 60G
            </li>
            <li>
              <img
                src="~assets/Karambitwarrioricon.png"
                class="gg"
                alt=""
              />爪刀勇士 花費 25F 10G → 30F 15G
            </li>
            <li>
              <img
                src="~assets/Unique-tech.jpg"
                class="gg"
                alt=""
              />印加<nuxt-link to="/techs/Couriers">金冠</nuxt-link>花費400F
              200G → 600F 600G
            </li>
            <li>
              <img
                src="~assets/Watchtowericon.png"
                class="gg"
                alt=""
              />韓國蓋塔時間60s → 75s (其他文明 80s)
            </li>
            <li>
              <img
                src="~assets/FishingShipIcon.jpg"
                class="gg"
                alt=""
              />義大利魚船花費60W → 64W (其他文明 75W)
            </li>
            <li>
              <img
                src="~assets/Coinage.jpg"
                class="gg"
                alt=""
              />鑄幣術移至城堡時代, 銀行技術移至帝王時代
            </li>
            <li>
              <img
                src="~assets/Farmicon.png"
                class="gg"
                alt=""
              />馬雅農夫效率修正成跟其他文明差不多
            </li>
            <li>
              <img
                src="~assets/FireGalleyIcon.jpg"
                class="gg"
                alt=""
              />火蒙衝對漁船傷害 3hp → 1hp
            </li>
            <li>
              <img
                src="~assets/CamelArcherIcon.jpg"
                class="gg"
                alt=""
              /><nuxt-link to="/units/Camel_Archer">精銳駱駝弓騎兵</nuxt-link
              >生產時間 21s → 25s
            </li>
            <li>
              <img
                src="~assets/CamelIcon.jpg"
                class="gg"
                alt=""
              />印度駱駝近防加成 +1 → +0
            </li>
            <li>
              <img
                src="~assets/Farmicon.png"
                class="gg"
                alt=""
              />斯拉夫農田加成倍率1.31 → 1.28
            </li>
          </ul>
          增強
          <ul>
            <li>
              <img
                src="~assets/RattanarcherIcon2.png"
                class="gg"
                alt=""
              />藤甲弓兵/精銳 血量 35/40 → 40/45
            </li>
            <li>
              <img
                src="~assets/Archery-range-logo.jpg"
                class="gg"
                alt=""
              />越南射箭場單位血量加成原本+10%/+15%/+20% → 皆 +20%
            </li>
            <li>
              <img
                src="~assets/ArbalestIcon.jpg"
                class="gg"
                alt=""
              />高棉得到強弩
            </li>
            <li>
              <img
                src="~assets/Siegetowericon.png"
                class="gg"
                alt=""
              />攻城塔半徑0.5 → 0.45 (變瘦，比較不會卡)
            </li>
            <li>
              <img
                src="~assets/lame.png"
                class="gg"
                alt=""
              />印加羊駝不再綁定鷹斥候
            </li>
            <li>
              <img
                src="~assets/ElephantArcherIcon.jpg"
                class="gg"
                alt=""
              />象弓騎兵係對反弓箭手類傷害的抵抗增加（從-2到0）；減少了對反騎兵弓箭手類傷害的抵抗（從0到-2）
            </li>
            <li>
              <img
                src="~assets/Saracenmamluk_icon.png"
                class="gg"
                alt=""
              />奴隸兵移除「騎兵」防禦類型 (原本會受到 剋騎兵傷害 但有 11
              防禦)，受到來自戟兵的傷害減少5點
            </li>
          </ul>
          其他
          <ul>
            <li>
              在沙漠且破裂的地形上的建築，被攻擊傷害+20%(<a
                href="https://www.youtube.com/watch?v=x7LWDiKiPy4"
                >影片說明</a
              >)
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allwide',
  components: {}
}
</script>
<style></style>
