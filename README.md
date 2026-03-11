<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yorica</title>
  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
      background: linear-gradient(180deg, #f5f7fb 0%, #eef5ff 100%);
      color: #1f2937;
      line-height: 1.7;
    }
    .container {
      max-width: 860px;
      margin: 0 auto;
      padding: 24px 16px 56px;
    }
    .hero {
      background: #ffffff;
      border-radius: 24px;
      padding: 32px 24px;
      box-shadow: 0 10px 28px rgba(0,0,0,0.06);
      text-align: center;
    }
    .app-name {
      margin: 0;
      font-size: 40px;
      font-weight: 700;
      color: #0f62fe;
      letter-spacing: 0.5px;
    }
    .tagline {
      margin: 10px 0 0;
      font-size: 18px;
      color: #4b5563;
    }
    .lead {
      margin: 20px auto 0;
      max-width: 680px;
      font-size: 16px;
      color: #374151;
    }
    .section {
      margin-top: 20px;
      background: #ffffff;
      border-radius: 20px;
      padding: 24px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.05);
    }
    h2 {
      margin: 0 0 12px;
      font-size: 22px;
      color: #111827;
    }
    p {
      margin: 0;
      font-size: 16px;
    }
    ul {
      margin: 12px 0 0;
      padding-left: 20px;
    }
    li {
      margin-bottom: 6px;
      font-size: 16px;
    }
    .links {
      display: grid;
      gap: 12px;
      margin-top: 16px;
    }
    .link-card {
      display: block;
      text-decoration: none;
      color: #111827;
      background: #f8fbff;
      border: 1px solid #dce9ff;
      border-radius: 16px;
      padding: 16px 18px;
      transition: transform 0.15s ease, box-shadow 0.15s ease;
    }
    .link-card:hover {
      transform: translateY(-1px);
      box-shadow: 0 8px 20px rgba(15, 98, 254, 0.08);
    }
    .link-title {
      font-size: 17px;
      font-weight: 700;
      color: #0f62fe;
      margin-bottom: 4px;
    }
    .link-desc {
      font-size: 14px;
      color: #4b5563;
    }
    .mail-box {
      margin-top: 14px;
      padding: 16px;
      border-radius: 14px;
      background: #eef5ff;
      border: 1px solid #d7e7ff;
    }
    a {
      color: #0f62fe;
      text-decoration: none;
    }
    .footer {
      margin-top: 24px;
      text-align: center;
      font-size: 14px;
      color: #6b7280;
    }
  </style>
</head>
<body>
  <div class="container">
    <section class="hero">
      <h1 class="app-name">Yorica</h1>
      <p class="tagline">最寄りから、やさしく行く。</p>
      <p class="lead">
        Yorica は、現在地から徒歩で最も近い都営交通接続点を起点に、
        目的地までの移動を分かりやすく案内するアプリです。
      </p>
    </section>

    <section class="section">
      <h2>Yorica について</h2>
      <p>
        徒歩で近い都営交通を優先して案内し、無理のない外出を支援します。
        徒歩距離のしきい値設定や、条件に応じた Appleマップへの誘導にも対応します。
      </p>
      <ul>
        <li>現在地から徒歩で最も近い都営交通接続点を案内</li>
        <li>目的地側で徒歩最寄りの都営接続点を案内</li>
        <li>徒歩距離しきい値を設定可能</li>
        <li>長い徒歩区間は Appleマップへ誘導</li>
      </ul>
    </section>

    <section class="section">
      <h2>各種ページ</h2>
      <div class="links">
        <a class="link-card" href="./support.html">
          <div class="link-title">サポート</div>
          <div class="link-desc">お問い合わせ先、不具合報告、ご要望はこちら</div>
        </a>

        <a class="link-card" href="./privacy.html">
          <div class="link-title">プライバシーポリシー</div>
          <div class="link-desc">位置情報や検索語句などの取り扱いについて</div>
        </a>

        <a class="link-card" href="./terms.html">
          <div class="link-title">利用規約</div>
          <div class="link-desc">アプリの利用条件と免責事項について</div>
        </a>
      </div>
    </section>

    <section class="section">
      <h2>お問い合わせ</h2>
      <div class="mail-box">
        <strong>メール：</strong>
        <a href="mailto:yorica.support@gmail.com">yorica.support@gmail.com</a>
      </div>
    </section>

    <div class="footer">
      © Yorica
    </div>
  </div>
</body>
</html>
    
  
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yorica プライバシーポリシー</title>
  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
      background: #f5f7fb;
      color: #1f2937;
      line-height: 1.8;
    }
    .container {
      max-width: 820px;
      margin: 0 auto;
      padding: 24px 16px 48px;
    }
    .card {
      background: #ffffff;
      border-radius: 20px;
      padding: 24px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.06);
    }
    h1 {
      margin: 0 0 8px;
      font-size: 30px;
      color: #0f62fe;
    }
    .tagline {
      margin: 0 0 24px;
      font-size: 15px;
      color: #6b7280;
    }
    h2 {
      margin-top: 28px;
      margin-bottom: 10px;
      font-size: 20px;
      color: #111827;
    }
    p, li {
      font-size: 16px;
    }
    ul {
      padding-left: 20px;
      margin: 10px 0 0;
    }
    .mail-box {
      margin-top: 18px;
      padding: 16px;
      border-radius: 14px;
      background: #eef5ff;
      border: 1px solid #d7e7ff;
    }
    a {
      color: #0f62fe;
      text-decoration: none;
    }
    .footer {
      margin-top: 28px;
      font-size: 14px;
      color: #6b7280;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <h1>Yorica プライバシーポリシー</h1>
      <p class="tagline">最寄りから、やさしく行く。</p>

      <p>
        Yorica（以下「本アプリ」）は、現在地から徒歩で最も近い都営交通接続点を起点に、
        目的地までの移動判断を支援するアプリです。
      </p>

      <h2>1. 取得する情報</h2>
      <p>本アプリでは、以下の情報を取得する場合があります。</p>
      <ul>
        <li>位置情報</li>
        <li>利用者が入力した検索語句（駅名、施設名、住所など）</li>
        <li>アプリの安定動作に必要な最小限の技術情報</li>
      </ul>

      <h2>2. 利用目的</h2>
      <ul>
        <li>現在地の表示</li>
        <li>徒歩で最も近い都営交通接続点の判定</li>
        <li>目的地検索結果の表示</li>
        <li>案内結果の表示</li>
        <li>徒歩距離しきい値に応じた Appleマップへの誘導</li>
      </ul>

      <h2>3. 第三者提供</h2>
      <p>
        本アプリは、法令に基づく場合を除き、取得した個人情報を第三者へ提供しません。
      </p>

      <h2>4. 外部サービス・公開データ</h2>
      <p>
        本アプリは、Apple の地図関連サービスおよび公共交通オープンデータ等を利用する場合があります。
        案内結果および時刻情報は参考情報であり、正確性・完全性を保証するものではありません。
      </p>

      <h2>5. 利用者による設定</h2>
      <p>
        利用者は、端末設定により位置情報の利用許可を変更できます。
        位置情報を許可しない場合、本アプリの主要機能が利用できない場合があります。
      </p>

      <h2>6. 改定</h2>
      <p>
        本ポリシーは、必要に応じて改定されることがあります。
      </p>

      <h2>7. お問い合わせ</h2>
      <div class="mail-box">
        <strong>メール：</strong>
        <a href="mailto:yorica.support@gmail.com">yorica.support@gmail.com</a>
      </div>

      <div class="footer">
        © Yorica
      </div>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yorica</title>
  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
      background: linear-gradient(180deg, #f5f7fb 0%, #eef5ff 100%);
      color: #1f2937;
      line-height: 1.7;
    }
    .container {
      max-width: 860px;
      margin: 0 auto;
      padding: 24px 16px 56px;
    }
    .hero {
      background: #ffffff;
      border-radius: 24px;
      padding: 32px 24px;
      box-shadow: 0 10px 28px rgba(0,0,0,0.06);
      text-align: center;
    }
    .app-name {
      margin: 0;
      font-size: 40px;
      font-weight: 700;
      color: #0f62fe;
      letter-spacing: 0.5px;
    }
    .tagline {
      margin: 10px 0 0;
      font-size: 18px;
      color: #4b5563;
    }
    .lead {
      margin: 20px auto 0;
      max-width: 680px;
      font-size: 16px;
      color: #374151;
    }
    .section {
      margin-top: 20px;
      background: #ffffff;
      border-radius: 20px;
      padding: 24px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.05);
    }
    h2 {
      margin: 0 0 12px;
      font-size: 22px;
      color: #111827;
    }
    p {
      margin: 0;
      font-size: 16px;
    }
    ul {
      margin: 12px 0 0;
      padding-left: 20px;
    }
    li {
      margin-bottom: 6px;
      font-size: 16px;
    }
    .links {
      display: grid;
      gap: 12px;
      margin-top: 16px;
    }
    .link-card {
      display: block;
      text-decoration: none;
      color: #111827;
      background: #f8fbff;
      border: 1px solid #dce9ff;
      border-radius: 16px;
      padding: 16px 18px;
      transition: transform 0.15s ease, box-shadow 0.15s ease;
    }
    .link-card:hover {
      transform: translateY(-1px);
      box-shadow: 0 8px 20px rgba(15, 98, 254, 0.08);
    }
    .link-title {
      font-size: 17px;
      font-weight: 700;
      color: #0f62fe;
      margin-bottom: 4px;
    }
    .link-desc {
      font-size: 14px;
      color: #4b5563;
    }
    .mail-box {
      margin-top: 14px;
      padding: 16px;
      border-radius: 14px;
      background: #eef5ff;
      border: 1px solid #d7e7ff;
    }
    a.mail {
      color: #0f62fe;
      text-decoration: none;
      font-weight: 600;
    }
    .footer {
      margin-top: 24px;
      text-align: center;
      font-size: 14px;
      color: #6b7280;
    }
  </style>
</head>
<body>
  <div class="container">
    <section class="hero">
      <h1 class="app-name">Yorica</h1>
      <p class="tagline">最寄りから、やさしく行く。</p>
      <p class="lead">
        Yorica は、現在地から徒歩で最も近い都営交通接続点を起点に、
        目的地までの移動を分かりやすく案内するアプリです。
      </p>
    </section>

    <section class="section">
      <h2>Yorica について</h2>
      <p>
        徒歩で近い都営交通を優先して案内し、無理のない外出を支援します。
        徒歩距離のしきい値設定や、条件に応じた Appleマップへの誘導にも対応します。
      </p>
      <ul>
        <li>現在地から徒歩で最も近い都営交通接続点を案内</li>
        <li>目的地側で徒歩最寄りの都営接続点を案内</li>
        <li>徒歩距離しきい値を設定可能</li>
        <li>長い徒歩区間は Appleマップへ誘導</li>
      </ul>
    </section>

    <section class="section">
      <h2>各種ページ</h2>
      <div class="links">
        <a class="link-card" href="./support.html">
          <div class="link-title">サポート</div>
          <div class="link-desc">お問い合わせ先、不具合報告、ご要望はこちら</div>
        </a>

        <a class="link-card" href="./privacy.html">
          <div class="link-title">プライバシーポリシー</div>
          <div class="link-desc">位置情報や検索語句などの取り扱いについて</div>
        </a>

        <a class="link-card" href="./terms.html">
          <div class="link-title">利用規約</div>
          <div class="link-desc">アプリの利用条件と免責事項について</div>
        </a>
      </div>
    </section>

    <section class="section">
      <h2>お問い合わせ</h2>
      <div class="mail-box">
        <strong>メール：</strong>
        <a class="mail" href="mailto:yorica.support@gmail.com">yorica.support@gmail.com</a>
      </div>
    </section>

    <div class="footer">
      © Yorica
    </div>
  </div>
</body>
</html>
  </div>
</body>
</html>