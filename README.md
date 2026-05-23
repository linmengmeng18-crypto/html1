[index.html](https://github.com/user-attachments/files/28171491/index.html)
# html1
AI Smart Work Portfolio
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>📊 Sales Dashboard</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: "Segoe UI", sans-serif;
      background: #f0f2f5;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background: linear-gradient(135deg, #1a73e8, #0d47a1);
      color: white;
      padding: 18px 32px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }

    header .title-wrap h1 { font-size: 22px; }
    header .title-wrap p  { font-size: 12px; opacity: 0.8; margin-top: 3px; }

    header .btn-open {
      background: white;
      color: #1a73e8;
      font-weight: 600;
      font-size: 13px;
      padding: 8px 18px;
      border-radius: 20px;
      text-decoration: none;
      transition: opacity 0.2s;
    }
    header .btn-open:hover { opacity: 0.85; }

    .iframe-wrapper {
      flex: 1;
      padding: 20px;
    }

    iframe {
      width: 100%;
      height: calc(100vh - 120px);
      border: none;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.1);
      background: white;
    }

    footer {
      text-align: center;
      font-size: 12px;
      color: #aaa;
      padding: 12px;
    }
  </style>
</head>
<body>

  <header>
    <div class="title-wrap">
      <h1>📊 Sales Dashboard</h1>
      <p>AppSheet_Dashboard_Sample · Google Apps Script 연동</p>
    </div>
    <a class="btn-open"
       href="https://script.google.com/macros/s/AKfycbzG0nmqYC9nSBBHNgQEAJV2JcUbYQeXi2I7IbgmqevpHGKtj7SqqQVvlLPJ3FXkyIBwnw/exec"
       target="_blank">
      새 탭에서 열기 ↗
    </a>
  </header>

  <div class="iframe-wrapper">
    <iframe
      src="https://script.google.com/macros/s/AKfycbzG0nmqYC9nSBBHNgQEAJV2JcUbYQeXi2I7IbgmqevpHGKtj7SqqQVvlLPJ3FXkyIBwnw/exec"
      title="Sales Dashboard"
      allowfullscreen>
    </iframe>
  </div>

  <footer>Powered by Google Apps Script · Hosted on Netlify</footer>

</body>
</html>
