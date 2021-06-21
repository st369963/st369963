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
          <li>安安, 我是 <b>@Jerry Cheng</b></li>
          <li>我的興趣有:睡覺、玩電腦、讀程式</li>
          <li>我現在是<b>資訊管理學系</b></li>
          <li>
            <b>我的工作經驗</b>
            <ul>
              <li>瓦斯行老闆</li>
              <li>口罩業務</li>
            </ul>
          </li>
          <li>
            <b>我的社團經驗</b>
            <ul>
              <li>中央學生會</li>
              <li>資管系學會</li>
            </ul>
          </li>
          <li>
            <b>目標</b>
            <ul>
              <li>考重機駕照</li>
              <li>大學畢業</li>
            </ul>
          </li>
          <li>
            <b>聯繫方式</b>
            <ul>
              <li>
                IG:
                <a href="https://www.instagram.com/godtoneasia/?hl=zh-tw">@godtoneasia</a>
              </li>
              <li>電話: 7777777</li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </body>
</html>
