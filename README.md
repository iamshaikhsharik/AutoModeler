<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Teachable Machine Docs</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f4f4f9;
      color: #333;
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }
    h1, h2 {
      color: #4b0082;
    }
    code {
      background: #eee;
      padding: 0.2em 0.4em;
      border-radius: 4px;
      font-size: 0.95em;
    }
    .section {
      margin-bottom: 2rem;
    }
    .card {
      background: white;
      border-radius: 12px;
      padding: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin: 1rem 0;
    }
    a {
      color: #0066cc;
    }
    .tutorial {
      background: #e0f7fa;
      padding: 0.8rem;
      border-left: 6px solid #00796b;
    }
  </style>
</head>
<body>

  <h1>📚 Teachable Machine Project Guide</h1>

  <div class="section card">
    <h2>🚀 Features</h2>
    <ul>
      <li>Train ML models in your browser (no coding needed)</li>
      <li>Image, audio, and pose classification</li>
      <li>Live preview and export options</li>
    </ul>
  </div>

  <div class="section card">
    <h2>🛠 Setup</h2>
    <p>To run locally:</p>
    <pre><code>git clone https://github.com/iamshaikhsharik/teachable-machine
cd teachable-machine
# Open index.html in your browser or use VS Code Live Server</code></pre>
  </div>

  <div class="section card">
    <h2>📦 Updated Dependencies</h2>
    <p>Latest TensorFlow.js CDN:</p>
    <pre><code>&lt;script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@4.19.0"&gt;&lt;/script&gt;</code></pre>
  </div>

  <div class="section card tutorial">
    <h2>🎓 Quick Tutorial: Train Your First Model</h2>
    <ol>
      <li>Open the app in your browser</li>
      <li>Click <strong>"Add Class"</strong> and record examples</li>
      <li>Press <strong>"Train Model"</strong></li>
      <li>Test in real-time and click <strong>"Export"</strong></li>
    </ol>
    <p><strong>Tips:</strong> Use varied lighting and positions while recording for best results.</p>
  </div>

  <div class="section card">
    <h2>🤝 Contributions</h2>
    <p>Want to help?</p>
    <ul>
      <li>Fork this repo</li>
      <li>Create a new branch: <code>feature/my-feature</code></li>
      <li>Push and open a Pull Request 🚀</li>
    </ul>
  </div>

  <div class="section card">
    <h2>🌐 Live Demo</h2>
    <p><em>Coming soon via GitHub Pages!</em> Want help deploying? Just ask!</p>
  </div>

</body>
</html>
