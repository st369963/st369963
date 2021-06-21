<!DOCTYPE html>
<html>
  <head>
    <title>Michael的自我介紹</title>
    <style>
      .container {
        display: flex;
        align-items: center;
        justify-content: center;
      }

      /* 網格退縮 */
      .col {
        width: 50%;
        margin: 20px;
      }

      /* 淡入顯示 */
      .fadeIn {
        animation: fadein 1s;
      }

      .fadeIn-slow {
        animation-delay: 1s;
      }

      .initHide {
        opacity: 0;
      }

      @keyframes fadein {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
    </style>
  </head>
  <body class="container">
    <div class="container" style="width: 80%; flex-direction: row">
      <div class="col fadeIn">
        <img src="./profile.jpeg" alt="My Photo" style="width: 100%" />
      </div>
      <div id="details" class="col fadeIn fadeIn-slow initHide">
        <h1>自我介紹</h1>
        <hr />
        <ul>
          <li>👋 Hi, 我是 <b>@Jerry Cheng</b></li>
          <li>👀 我的興趣是高爾夫、撞球、跑步</li>
          <li>🌱 我目前是<b>國立中央大學資訊管理學系學生</b></li>
          <li>
            <b>📁 我的工作經驗有</b>
            <ul>
              <li>特麗帆有限公司助理</li>
              <li>金展達有限公司業務</li>
            </ul>
          </li>
          <li>
            <b>🤽‍♀️ 我的社團經驗有</b>
            <ul>
              <li>曾經熱舞H舵成員</li>
              <li>2019年中央資管公關部</li>
              <li>2019年資管嘉年華公關組</li>
              <li>2020年資管迎新宿營輔員組</li>
              <li>2020年資管迎新交際舞負責人</li>
              <li>資管機械聯合鬼屋活動組</li>
              <li>資管傳情行銷組</li>
              <li>中友第13屆迎新美輔組</li>
              <li>中友第13屆迎新營火舞組員</li>
              <li>中友第13屆返服組長</li>
            </ul>
          </li>
          <li>
            <b>⤴ 未來目標有</b>
            <ul>
              <li>考取外文相關證照、公司相關所需要的證照</li>
              <li>使說話變得更有說服力</li>
              <li>任何事都要嘗試，成為全能的人</li>
              <li>規劃好時間，做事更有效率</li>
              <li>用心待人，別人才會用心待你</li>
            </ul>
          </li>
          <li>
            <b>📫 如何聯繫我</b>
            <ul>
              <li>
                Email:
                <a href="michael900314@gmail.com">michael900314@gmail.com</a>
              </li>
              <li>電話: 0933080610</li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
    <script>
      window.onload = () => {
        setTimeout(() => {
          var detail = document.querySelector("#details");
          detail.classList.remove("initHide");
        }, 2000);
      };
    </script>
  </body>
</html>
