<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Smart Blog Web Setup</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
    }
    h1, h2 {
      color: #2c3e50;
    }
    code {
      background: #eaeaea;
      padding: 2px 5px;
      border-radius: 4px;
      font-size: 0.95em;
    }
    pre {
      background: #eaeaea;
      padding: 10px;
      border-radius: 4px;
      overflow-x: auto;
    }
    a {
      color: #3498db;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .note {
      background: #fff3cd;
      border-left: 5px solid #ffeeba;
      padding: 10px;
      margin-top: 10px;
      border-radius: 4px;
    }
  </style>
</head>
<body>

  <h1>Smart Blog Web Setup</h1>
  
  <p>Repository link: <a href="https://github.com/shamodhas-ijse-teaching/smart-blog-web-72" target="_blank">Smart Blog Web</a></p>

  <h2>Project Structure</h2>
  <pre>
smart-blog-web-72/
├── frontend/    # React/Vite Frontend
└── backend/     # Node/Express Backend
  </pre>

  <h2>Frontend (FE) Setup</h2>
  <ol>
    <li>Open terminal in <code>frontend</code> folder.</li>
    <li>If <code>node_modules</code> folder is missing, run: <pre>npm install</pre></li>
    <li>Optional: open VS Code: <pre>code .</pre></li>
    <li>Start development server: <pre>npm run dev</pre></li>
  </ol>

  <h2>Backend (BE) Setup</h2>
  <ol>
    <li>Open terminal in <code>backend</code> folder.</li>
    <li>If <code>node_modules</code> folder is missing, run: <pre>npm install</pre></li>
    <li>Optional: open VS Code: <pre>code .</pre></li>
    <li>Start backend server: <pre>npm run dev</pre></li>
  </ol>

  <div class="note">
    ⚠️ Note: Run Frontend and Backend in separate terminals. Make sure Node.js ≥ 18 is installed. If backend uses <code>.env</code>, copy <code>.env.example</code> → <code>.env</code> and fill in required values.
  </div>

</body>
</html>
