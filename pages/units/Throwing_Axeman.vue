<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>擲斧兵</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            擲斧兵是<nuxt-link to="/civs/Franks">法蘭克</nuxt-link
            >的特殊單位，能夠在<nuxt-link to="/techs/age/Castle_Age"
              >城堡時代</nuxt-link
            >的
            <nuxt-link to="/building/Castle">城堡</nuxt-link
            >中訓練。擲斧兵是一個有範圍近戰攻擊的步兵單位。擲斧兵可以在<nuxt-link
              to="/techs/age/Imperial_Age"
              >帝王時代</nuxt-link
            >升級為精銳擲斧兵。
          </p>
        </div>
        <h3>戰術要點</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              擲斧兵的攻擊屬於範圍近戰傷害，面對大多數傳統的反射手單位（<nuxt-link
                to="/units/Elite_Skirmisher"
                >戰矛兵</nuxt-link
              >和哥德衛隊
              <nuxt-link to="/units/Huskarl">哥德衛隊</nuxt-link
              >）有奇效。此外，由於擲斧兵對<nuxt-link to="/building"
                >建築物</nuxt-link
              >有攻擊加成，因此大量的擲斧兵可以作為攻城武器的替代品。
            </li>
            <li>
              擲斧兵可以在城牆後迅速摧毀衝撞車，因為衝撞車的遠程護甲在他們眼中猶如不存在般。他們比一般的射手單位對建築物造成的傷害還要多。然而，擲斧兵較短的攻擊範圍意味著他們對於近身單位，攻城武器以及採用打帶跑戰術的射手單位都很脆弱。他們不像
              <nuxt-link to="/units/Archer">弓箭手</nuxt-link
              >那樣容易被攻城器殺死（需要兩次才能被擊倒），但<nuxt-link
                to="/units/Mangonel"
                >投石車</nuxt-link
              >仍然可以一擊必殺他們。然而，擲斧兵只要能夠避免被擊中並能夠縮小作戰距離，就可以通過近戰傷害輕易地摧毀這些攻城武器。重裝騎兵單位(
              <nuxt-link to="/units/Hussar">匈牙利輕騎兵</nuxt-link
              >除外)如<nuxt-link to="/units/Paladin">遊俠</nuxt-link
              >也能有效對付擲斧兵。
            </li>
            <li>
              由於法蘭克人相當依賴遊俠，所以使用投擲斧兵來對付<nuxt-link
                to="/units/Camel"
                >駱駝</nuxt-link
              >和<nuxt-link to="/units/Halberdier">戟兵</nuxt-link
              >是非常有用的對策。
            </li>
            <li>擲斧兵的開火間隔太長，不適合用來風箏近戰單位。</li>
            <li>
              擲斧兵拿來打<nuxt-link to="/units/Huskarl">哥德衛隊</nuxt-link
              >相當好用。
            </li>
          </ul>
        </div>
        <h3>更多數據</h3>
        <div class="hrn1"></div>
        <div class="n1"></div>
        <table class="table-bordered" width="100%">
          <tr class="tta">
            <td class="unit" colspan="2" style="text-align: center;">
              <div class="unititle">劣勢與優勢</div>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:30%">強勢(容易對抗)</td>
            <td class="tta4">
              <nuxt-link to="/units/Skirmisher">矛兵</nuxt-link>、<nuxt-link
                to="/units/Halberdier"
                >戟兵</nuxt-link
              >、<nuxt-link to="/units/Eagle_Warrior">鷹勇士</nuxt-link>、
              <nuxt-link to="/units/Battering_Ram">衝撞車</nuxt-link
              >、<nuxt-link to="/units/Trebuchet">巨型投石機</nuxt-link
              >、<nuxt-link to="/building">建築物</nuxt-link>、
              <nuxt-link to="/units/Light_Cavalry">輕騎兵</nuxt-link
              >、<nuxt-link to="/units/Huskarl">哥德衛隊</nuxt-link>和<nuxt-link
                to="/units/Camel"
                >駱駝騎兵</nuxt-link
              >。
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:30%">劣勢(不易對抗)</td>
            <td class="tta4">
              <nuxt-link to="/units/Archer">弓箭手</nuxt-link>、<nuxt-link
                to="/units/Jaguar_Warrior"
                >豹勇士</nuxt-link
              >、<nuxt-link to="/units/Hand_Cannoneer">火槍兵</nuxt-link>、
              <nuxt-link to="/units/Conquistador">西班牙征服者</nuxt-link
              >、<nuxt-link to="/units/Slinger">投石手</nuxt-link>、<nuxt-link
                to="/units/Boyar"
                >貴族鐵騎</nuxt-link
              >、
              <nuxt-link to="/units/Cataphract">聖騎兵</nuxt-link>、<nuxt-link
                to="/units/Samurai"
                >日本武士</nuxt-link
              >、<nuxt-link to="/units/Teutonic_Knight">條頓武士</nuxt-link>。
            </td>
          </tr>
          <tr class="tta">
            <td class="unit" colspan="2" style="text-align: center;">
              <div class="unititle">升級</div>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">攻擊力</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Forging.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Forging">鍛造</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Ironcasting.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Iron_Casting">鑄造</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Blastfurnace.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Blast_Furnace">鼓風爐</nuxt-link>(+2)
              <br />
              <img
                class="gg"
                src="~assets/Arson.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Arson">縱火</nuxt-link
              >:步兵+2攻擊vs<nuxt-link to="/armor/Armor_Class_Standard_Building"
                >標準建築</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">範圍</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Unique-tech.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bearded_Axe">倒鉤斧</nuxt-link>(+1)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">防禦</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Scalemailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Scale_Mail_Armor">步兵鱗甲</nuxt-link
              >(+1/+1) <br />
              <img
                class="gg"
                src="~assets/Chainmailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Chain_Mail_Armor">步兵鎖甲</nuxt-link
              >(+1/+1) <br />
              <img
                class="gg"
                src="~assets/Platemailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Plate_Mail_Armor">步兵板甲</nuxt-link
              >(+1/+2)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">速度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Squires.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Squires">護衛</nuxt-link>(+10%)
            </td>
          </tr>
          <tr></tr>
          <tr>
            <td class="tta1" style="width:10%">視野</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Tracking.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Tracking">追蹤技術</nuxt-link>(+2)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">招降抵抗</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Faith.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Faith">忠誠信仰</nuxt-link> <br />
              <img
                class="gg"
                src="~assets/Heresy.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Heresy">異端邪說</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">生產速度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Conscription.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link>(+33%)
            </td>
          </tr>
        </table>

        <h3>剋擲斧兵的單位與建築</h3>
        <div class="hrn1"></div>
        <div class="n1 bonuses">
          以下單位擁有對擲斧兵的額外傷害，按造傷殺力排列。
          <div class="n1">
            <div class="row">
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+15攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/CannonGalleonIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Cannon_Galleon">火砲戰船</nuxt-link
                    >→
                    <img
                      class="gg"
                      src="~assets/CannonGalleonIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Elite_Cannon_Galleon"
                      >精銳火砲戰船</nuxt-link
                    >
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+12攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/CataphractIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Cataphract">精銳聖騎兵</nuxt-link
                    >(<nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link>限定)
                  </li>
                  <li>
                    <img class="gg" src="~assets/SMURI.jpg" alt="" /><nuxt-link
                      to="/units/Samurai"
                      >精銳日本武士</nuxt-link
                    >(<nuxt-link to="/civs/Japanese">日本</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+11攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/JaguarWarriorIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Jaguar_Warrior"
                      >精銳豹勇士</nuxt-link
                    >(<nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+10攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/HandCannoneerIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Hand_Cannoneer">火槍兵</nuxt-link>
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/Slingericon.png"
                      alt=""
                    /><nuxt-link to="/units/Slinger">投石手</nuxt-link
                    >(<nuxt-link to="/civs/Incas">印加</nuxt-link>限定)
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/JaguarWarriorIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Jaguar_Warrior">豹勇士</nuxt-link
                    >(<nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link>限定)
                  </li>
                  <li>
                    <img class="gg" src="~assets/SMURI.jpg" alt="" /><nuxt-link
                      to="/units/Samurai"
                      >日本武士</nuxt-link
                    >(<nuxt-link to="/civs/Japanese">日本</nuxt-link>限定)
                  </li>
                </ul>
              </div>
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+9攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/CataphractIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Cataphract">聖騎兵</nuxt-link
                    >(<nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+2攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/PlumedArcherIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Plumed_Archer"
                      >精銳羽毛箭射手</nuxt-link
                    >(<nuxt-link to="/civs/Mayans">馬雅</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+1攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/PlumedArcherIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Plumed_Archer">羽毛箭射手</nuxt-link
                    >(<nuxt-link to="/civs/Mayans">馬雅</nuxt-link>限定)
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        以下技術可讓以下單位對擲斧兵有額外攻擊力
        <div class="n1">
          <img class="gg" src="~assets/Unique-tech.jpg" width="22" alt="" />
          <nuxt-link to="/techs/Logistica">後勤學</nuxt-link>
          <div style="margin:12px 0px;"><strong>+6攻擊</strong></div>
          <ul>
            <li>
              <img
                class="gg"
                src="~assets/CataphractIcon.jpg"
                alt=""
              /><nuxt-link to="/units/Cataphract">聖騎兵</nuxt-link>→
              <img
                class="gg"
                src="~assets/CataphractIcon.jpg"
                alt=""
              /><nuxt-link to="/units/Cataphract">精銳聖騎兵</nuxt-link
              >(<nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link>限定)
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
              >能夠提高擲斧兵的生產速度還有加速
              <nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link
              >、<nuxt-link to="/techs/Bearded_Axe">倒鉤斧</nuxt-link
              >科技研究時間(快25%)。
            </li>
            <li>
              <nuxt-link to="/civs/Goths">哥德</nuxt-link>：研發科技<nuxt-link
                to="/techs/Tracking"
                >追蹤技術</nuxt-link
              >、<nuxt-link to="/techs/Squires">護衛</nuxt-link>、
              <nuxt-link to="/techs/Arson">縱火</nuxt-link>的時間快20%。
            </li>
            <li>
              <nuxt-link to="/civs/Teutons">條頓</nuxt-link
              >：擲斧兵更不容易被招降。
            </li>
          </ul>
        </div>
        <h3>更新日誌</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>
            <em><nuxt-link to="/games/aok">帝王世紀</nuxt-link></em>
          </h3>
          <ul>
            <li>擲斧兵有50(精銳是60)HP。</li>
            <li>擲斧兵移動速度為0.9。</li>
            <li>
              擲斧兵(非精銳)的<nuxt-link to="/elements/Frame_delay"
                >開火間隔</nuxt-link
              >為12。
            </li>
            <li>升級精銳擲斧兵需要1000食物和850黃金。</li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/aoc">征服者入侵</nuxt-link></em>
          </h3>
          <ul>
            <li>引入<nuxt-link to="/techs/Heresy">異端邪說</nuxt-link>。</li>
            <li>
              <nuxt-link to="/units/hero/Friar_Tuck">法蘭克</nuxt-link
              >:引入<nuxt-link to="/techs/Bearded_Axe">倒鉤斧</nuxt-link>。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/aof">失落的帝國</nuxt-link></em>
          </h3>
          <ul>
            <li>擲斧兵(非精銳)的開火間隔為10秒。</li>
            <li>升級精銳擲斧兵需要1000食物和750黃金。</li>
            <li>
              <nuxt-link to="/units/hero/Friar_Tuck">法蘭克</nuxt-link
              >:得到<nuxt-link to="/techs/Squires">護衛</nuxt-link>技術。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/ak">非洲王國</nuxt-link></em>
          </h3>
          <ul>
            <li>擲斧兵現在的移動速度為1。</li>
            <li>引入<nuxt-link to="/techs/Arson">縱火</nuxt-link>。</li>
            <li>4.8版本後擲斧兵有60(精銳是70)HP。</li>
          </ul>
        </div>
        <h3>豆知識</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              在沙拉丁，巴巴羅薩和聖女貞德的時代，法蘭克人並沒有在戰鬥中投擲斧頭。
            </li>
            <li>
              實際上， francisca
              的命名是因為它被法蘭克斯（其名字的意思是“長矛”，與斯拉夫教會的“桿子”同源）使用。
            </li>
            <li>
              在現實生活中，francisca只有一個刀片，體積更小，重量更輕：平均長度為17英寸，重量約為1.3磅。
            </li>
          </ul>
        </div>
        <h3>歷史</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <p>
            法蘭克人從古代就把斧頭作為他們的首選武器。歐洲進入黑暗時代後他們仍繼續使用斧頭，他們的戰士們因為會在戰鬥向敵人丟擲斧頭而出名。一個強壯的男人可以把斧頭投擲得很遠。法蘭克部隊通常帶著好幾個斧頭，並在一對一的戰鬥中使用。隨著他們的進步，他們可以接起投擲過的斧頭來補充彈藥量。擲斧兵對身輕裝的小型部隊特別有用。攜帶斧頭對於拆除防禦工事也很有用。
          </p>
        </div>
        <h3>實戰影片</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <p><em>擲斧兵對飛刀女獵手</em></p>
          <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/O6tsFsGSC1E"
            frameborder="0"
            allow="autoplay; encrypted-media"
            allowfullscreen
          ></iframe>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td
              class="unit"
              colspan="2"
              style="background-color:#3c763d;text-align: center;"
            >
              <div class="unititle" style="color: #fff">擲斧兵</div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/TAXEM.jpg" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td
              class="unit"
              colspan="2"
              style="background-color:#3c763d;text-align: center;"
            >
              <div class="unititle2" style="color: #fff">單位介紹</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">
              <nuxt-link to="/units/Infantry_Units">步兵</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">
              <nuxt-link to="/civs/Franks">法蘭克</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Castle-age-reseach.jpg"
                alt=""
              /><nuxt-link to="/techs/age/Castle_Age">城堡時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練於</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Castleicon.png"
                width="45"
                alt=""
              /><nuxt-link to="/building/Castle">城堡</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練時間</td>
            <td class="unit4">17秒</td>
          </tr>
          <tr>
            <td
              class="unit"
              colspan="2"
              style="background-color:#3c763d;text-align: center;"
            >
              <div class="unititle2" style="color: #fff">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">食物</td>
            <td class="unit4">55</td>
          </tr>
          <tr>
            <td class="unit3">黃金</td>
            <td class="unit4">25</td>
          </tr>
          <tr>
            <td
              class="unit"
              colspan="2"
              style="background-color:#3c763d;text-align: center;"
            >
              <div class="unititle2" style="color: #fff">數據</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">60/70(精銳)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊</td>
            <td class="unit4">7/8(精銳)(近戰)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊加成</td>
            <td class="unit4">
              對<nuxt-link to="/armor/Armor_Class_Standard_Building"
                >標準建築 </nuxt-link
              >+1/+2(精銳) <br />對<nuxt-link
                to="/armor/Armor_Class_Eagle_Warrior"
                >鷹勇士</nuxt-link
              >+1/+2(精銳)
            </td>
          </tr>
          <tr>
            <td class="unit3">攻擊速度</td>
            <td class="unit4">2.03</td>
          </tr>
          <tr>
            <td class="unit3">開火間隔</td>
            <td class="unit4">10/8(精銳)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊範圍</td>
            <td class="unit4">3/4(精銳)</td>
          </tr>
          <tr>
            <td class="unit3">命中率</td>
            <td class="unit4">100%</td>
          </tr>
          <tr></tr>
          <tr>
            <td class="unit3">發射速度</td>
            <td class="unit4">7</td>
          </tr>
          <tr>
            <td class="unit3">近防</td>
            <td class="unit4">0/1(精銳)</td>
          </tr>
          <tr>
            <td class="unit3">遠防</td>
            <td class="unit4">0</td>
          </tr>
          <tr>
            <td class="unit3">護甲分類</td>
            <td class="unit4">
              <nuxt-link to="/armor/Armor_Class_Infantry">步兵</nuxt-link>
              <br />
              <nuxt-link to="/armor/Armor_Class_Unique_Unit"
                >特殊單位</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">跑速</td>
            <td class="unit4">1</td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">5/6(精銳)</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2">單位演變</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">升級到</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/TAXEM.jpg"
                width="45"
                alt=""
              />精銳擲斧兵
            </td>
          </tr>
          <tr>
            <td class="unit3">升級成本</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Elite-unique-research.jpg"
                alt=""
              />1000食物750黃金
            </td>
          </tr>
          <tr>
            <td class="unit3">升級時間</td>
            <td class="unit4">45秒</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由賜齡協助編輯</div>
      </div>
      <div class="col-md-12">
        <h3>圖庫</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <div class="col-md-4">
            <gallery
              ><img
                class="imgn hg"
                width="180"
                src="~assets/Throwingaxeman.png"
                alt=""
            /></gallery>
            <div class="lightbox-caption" style="width:220px">
              <p><em>一群擲斧兵。</em></p>
            </div>
          </div>
          <div class="col-md-4">
            <gallery
              ><img
                class="imgn hg"
                width="200"
                src="~assets/Francisca.jpg"
                alt=""
            /></gallery>
            <div class="lightbox-caption" style="width:185px">
              <p>
                <em>真實的斧頭(francisca)比遊戲中描繪的更小且只有單一刀片。</em>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allunit',
  components: {}
}
</script>
<style></style>
