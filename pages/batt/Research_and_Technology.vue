<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>研發與科技</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            <b>研發與科技</b
            >是華勒斯教學戰役的第四個劇情關卡，專為那些從未玩過“世紀帝國”遊戲的玩家設計，教導玩家如何研發科技與升級時代。
          </p>
        </div>
        <h2>玩家</h2>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>基本資訊</h3>
          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc1" width="14%">起始時代：</td>
              <td class="tc2" width="14%">黑暗時代</td>
              <td class="tc1" width="14%">起始資源：</td>
              <td class="tc2">200木材，450食物，250黃金，200石頭</td>
              <td class="tc1" width="14%">人口上限：</td>
              <td class="tc2" width="5%">75</td>
            </tr>
          </table>

          <p></p>
          <h3>AI</h3>
          <!--<span class="glyphicon glyphicon-star" aria-hidden="true" style="color: #ff911d; margin-left: 5px;"></span>:中立</p>!-->
          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc4" colspan="4" style="background: #2980b9;">
                玩家本身
              </td>
            </tr>
            <tr>
              <td class="tc6"><div class="p1">玩家1</div></td>
              <td class="tc6" colspan="3">塞爾特人（藍色）</td>
            </tr>
            <tr>
              <td class="tc4" colspan="4" style="background:#ea6153;">敵對</td>
            </tr>
            <tr>
              <td class="tc6"><div class="p2">玩家2</div></td>
              <td class="tc6">英格蘭（紅色）不列顛</td>
            </tr>
          </table>

          <br />
          <dl class="dl-horizontal">
            <dt>開場單位：</dt>
            <dd>8位村民、8位民兵。</dd>
            <dt>大地之母單位：</dt>
            <dd>無。</dd>
          </dl>
          <h3>主要任務</h3>
          <div class="hrn1"></div>
          <div class="n1">
            <ol>
              <li>
                要達成本項任務，您必須升級至封建時代，並且擊敗來犯的英格蘭軍隊。
              </li>
            </ol>
          </div>
        </div>
        <h3>任務提示</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>你的士兵將會自動攻擊任何接近他們的敵國士兵。</li>
            <li>
              你也可以選按你的士兵，然後在特定的敵軍單位上按滑鼠右鍵以朝之攻擊。
            </li>
          </ul>
          <h3>芝麻小事</h3>
          <div class="hrn1"></div>
          <ul>
            <li>此關英格蘭在字幕上被稱為英國人（但仍被語音稱為英格蘭人）。</li>
            <li>
              外面是沙漠地區，前往到西北地區，那裡有一個的英格蘭士兵被樹木包圍著。
            </li>
            <li>
              玩家可以砍伐樹木，殺死士兵贏得勝利。儘管如此，完成上述目標的速度更快，更容易
            </li>
            <li>在整個遊戲中，速度不能改變。</li>
          </ul>
          <p></p>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                研發與科技
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Wallacelc4map.png" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">情景信息</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">版本</td>
            <td class="unit4">
              <nuxt-link to="/games/aok">帝王世紀</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">戰役</td>
            <td class="unit4">
              <nuxt-link to="/batt/William_Wallacea">威廉華勒斯</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">
              <nuxt-link to="/civs/Celts">塞爾特人</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                戰役關卡編號
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">章節</td>
            <td class="unit4">帝王世紀第一章之四</td>
          </tr>
          <tr>
            <td class="unit3">上一關</td>
            <td class="unit4">
              <nuxt-link to="/batt/Training_the_Troops">訓練軍隊</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">下一關</td>
            <td class="unit4">
              <nuxt-link to="/batt/The_Battle_of_Stirling"
                >斯特林之役</nuxt-link
              >
            </td>
          </tr>
        </table>

        <div class="thanks">感謝！此頁面由裕暉、亞諭協助編輯。</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allbatt',
  components: {}
}
</script>
<style></style>
