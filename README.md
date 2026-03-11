<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yorica</title>
  <style>
    :root {
      --bg1: #f5f7fb;
      --bg2: #eef5ff;
      --card: #ffffff;
      --text: #1f2937;
      --sub: #4b5563;
      --line: #dce9ff;
      --accent: #0f62fe;
      --accent-soft: #eef5ff;
      --shadow: 0 10px 28px rgba(0, 0, 0, 0.06);
      --radius: 22px;
    }

    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
      background: linear-gradient(180deg, var(--bg1) 0%, var(--bg2) 100%);
      color: var(--text);
      line-height: 1.8;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 24px 16px 56px;
    }

    .hero,
    .section {
      background: var(--card);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
    }

    .hero {
      padding: 34px 24px;
      text-align: center;
    }

    .app-name {
      margin: 0;
      font-size: 42px;
      font-weight: 700;
      color: var(--accent);
      letter-spacing: 0.5px;
    }

    .tagline {
      margin: 10px 0 0;
      font-size: 18px;
      color: var(--sub);
    }

    .lead {
      margin: 20px auto 0;
      max-width: 700px;
      font-size: 17px;
      color: #374151;
    }

    .section {
      margin-top: 20px;
      padding: 24px;
    }

    h2 {
      margin: 0 0 14px;
      font-size: 28px;
      color: #111827;
      border-bottom: 1px solid #e5e7eb;
      padding-bottom: 10px;
    }

    h3 {
      margin: 22px 0 10px;
      font-size: 22px;
      color: #111827;
    }

    p {
      margin: 0 0 12px;
      font-size: 16px;
    }

    ul {
      margin: 10px 0 0;
      padding-left: 24px;
    }

    li {
      margin-bottom: 8px;
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
      border: 1px solid var(--line);
      border-radius: 16px;
      padding: 16px 18px;
      transition: transform 0.15s ease, box-shadow 0.15s ease;
    }

    .link-card:hover {
      transform: translateY(-1px);
      box-shadow: 0 8px 20px rgba(15, 98, 254, 0.08);
    }

    .link-title {
      font-size: 18px;
      font-weight: 700;
      color: var(--accent);
      margin-bottom: 4px;
    }

    .link-desc {
      font-size: 14px;
      color: var(--sub);
    }

    .mail-box {
      margin-top: 14px;
      padding: 16px;
      border-radius: 14px;
      background: var(--accent-soft);
      border: 1px solid #d7e7ff;
      font-size: 18px;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    .note {
      margin-top: 10px;
      color: var(--sub);
      font-size: 15px;
    }

    .footer {
      margin-top: 24px;
      text-align: center;
      font-size: 14px;
      color: #6b7280;
    }

    .small-nav {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 18px;
      justify-content: center;
    }

    .small-nav a {
      background: #f8fbff;
      border: 1px solid var(--line);
      color: var(--accent);
      padding: 10px 14px;
      border-radius: 999px;
      font-size: 14px;
      font-weight: 600;
    }

    @media (max-width: 640px) {
      .app-name {
        font-size: 36px;
      }

      h2 {
        font-size: 24px;
      }

      h3 {
        font-size: 20px;
      }

      .hero,
      .section {
        border-radius: 18px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <section class="hero" id="top">
      <h1 class="app-name">Yorica</h1>
      <p class="tagline">最寄りから、やさしく行く。</p>
      <p class="lead">
        Yorica は、現在地から徒歩で最も近い都営交通接続点を起点に、
        目的地までの移動を分かりやすく案内するアプリです。
      </p>

      <div class="small-nav">
        <a href="#support">サポート</a>
        <a href="#privacy">プライバシーポリシー</a>
        <a href="#terms">利用規約</a>
        <a href="#contact">お問い合わせ</a>
      </div>
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
        <a class="link-card" href="#support">
          <div class="link-title">サポート</div>
          <div class="link-desc">お問い合わせ先、不具合報告、ご要望はこちら</div>
        </a>

        <a class="link-card" href="#privacy">
          <div class="link-title">プライバシーポリシー</div>
          <div class="link-desc">位置情報や検索語句などの取り扱いについて</div>
        </a>

        <a class="link-card" href="#terms">
          <div class="link-title">利用規約</div>
          <div class="link-desc">アプリの利用条件と免責事項について</div>
        </a>
      </div>
    </section>

    <section class="section" id="support">
      <h2>Yorica サポート</h2>
      <p>最寄りから、やさしく行く。</p>
      <p>
        Yorica は、現在地から徒歩で最も近い都営交通接続点を起点に、
        目的地までの移動を分かりやすく案内するアプリです。
      </p>

      <h3>お問い合わせ</h3>
      <p>
        ご不明点、不具合報告、ご意見・ご要望がある場合は、下記までご連絡ください。
      </p>

      <div class="mail-box">
        <strong>メール：</strong>
        <a href="mailto:yorica.support@gmail.com">yorica.support@gmail.com</a>
      </div>

      <h3>ご連絡時にご記載いただきたい内容</h3>
      <ul>
        <li>ご利用端末</li>
        <li>iOS バージョン</li>
        <li>アプリバージョン</li>
        <li>発生した事象の内容</li>
        <li>発生時の操作手順</li>
      </ul>

      <h3>件名例</h3>
      <ul>
        <li>【Yorica】不具合報告</li>
        <li>【Yorica】お問い合わせ</li>
        <li>【Yorica】ご要望</li>
      </ul>

      <h3>ご注意</h3>
      <p>
        案内情報は参考情報です。実際の運行状況や現地案内もあわせてご確認ください。
      </p>
    </section>

    <section class="section" id="privacy">
      <h2>Yorica プライバシーポリシー</h2>
      <p>
        Yorica（以下「本アプリ」）は、現在地から徒歩で最も近い都営交通接続点を起点に、
        目的地までの移動判断を支援するアプリです。
      </p>

      <h3>1. 取得する情報</h3>
      <p>本アプリでは、以下の情報を取得する場合があります。</p>
      <ul>
        <li>位置情報</li>
        <li>利用者が入力した検索語句（駅名、施設名、住所など）</li>
        <li>アプリの安定動作に必要な最小限の技術情報</li>
      </ul>

      <h3>2. 利用目的</h3>
      <ul>
        <li>現在地の表示</li>
        <li>徒歩で最も近い都営交通接続点の判定</li>
        <li>目的地検索結果の表示</li>
        <li>案内結果の表示</li>
        <li>徒歩距離しきい値に応じた Appleマップへの誘導</li>
      </ul>

      <h3>3. 第三者提供</h3>
      <p>
        本アプリは、法令に基づく場合を除き、取得した個人情報を第三者へ提供しません。
      </p>

      <h3>4. 外部サービス・公開データ</h3>
      <p>
        本アプリは、Apple の地図関連サービスおよび公共交通オープンデータ等を利用する場合があります。
        案内結果および時刻情報は参考情報であり、正確性・完全性を保証するものではありません。
      </p>

      <h3>5. 利用者による設定</h3>
      <p>
        利用者は、端末設定により位置情報の利用許可を変更できます。
        位置情報を許可しない場合、本アプリの主要機能が利用できない場合があります。
      </p>

      <h3>6. 改定</h3>
      <p>本ポリシーは、必要に応じて改定されることがあります。</p>

      <h3>7. お問い合わせ</h3>
      <div class="mail-box">
        <strong>メール：</strong>
        <a href="mailto:yorica.support@gmail.com">yorica.support@gmail.com</a>
      </div>
    </section>

    <section class="section" id="terms">
      <h2>Yorica 利用規約</h2>
      <p>
        Yorica（以下「本アプリ」）は、現在地から徒歩で最も近い都営交通接続点を起点として、
        目的地までの移動判断を支援するアプリです。
      </p>

      <h3>1. 本アプリの内容</h3>
      <p>
        本アプリは、位置情報、Apple の地図関連サービス、公共交通オープンデータ等をもとに、
        移動判断の参考情報を表示します。
      </p>

      <h3>2. 位置情報の利用</h3>
      <p>
        本アプリは、現在地表示、最寄り都営交通接続点の判定、目的地までの案内表示等のために
        位置情報を利用することがあります。
      </p>

      <h3>3. 案内情報について</h3>
      <p>
        本アプリで表示される案内、時刻、停留所情報、経路情報その他の情報は参考情報であり、
        その正確性、完全性、有用性、最新性を保証するものではありません。
      </p>

      <h3>4. 外部サービス</h3>
      <p>
        本アプリは、Appleマップその他の外部サービスへ遷移する場合があります。
        外部サービスの利用に関しては、各サービス提供者の利用条件等が適用されます。
      </p>

      <h3>5. 免責</h3>
      <p>
        実際の移動にあたっては、現地の案内、運行事業者の公式情報、交通状況等をあわせてご確認ください。
        本アプリの利用により生じた損害について、運営者に故意または重過失がある場合を除き、責任を負いません。
      </p>

      <h3>6. 本アプリの変更・停止</h3>
      <p>
        運営者は、利用者に事前に通知することなく、本アプリの内容を変更し、
        または提供を中断・終了することがあります。
      </p>

      <h3>7. お問い合わせ</h3>
      <div class="mail-box">
        <strong>メール：</strong>
        <a href="mailto:yorica.support@gmail.com">yorica.support@gmail.com</a>
      </div>
    </section>

    <section class="section" id="contact">
      <h2>お問い合わせ</h2>
      <div class="mail-box">
        <strong>メール：</strong>
        <a href="mailto:yorica.support@gmail.com">yorica.support@gmail.com</a>
      </div>
      <p class="note">
        App Store Connect に入れる URL は、このトップページURLで進められます。
      </p>
    </section>

    <div class="footer">
      © Yorica
    </div>
  </div>
</body>
</html>