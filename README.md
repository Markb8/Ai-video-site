# Ai-video-site 
index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>AI Video Creator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      padding: 40px;
      text-align: center;
    }
    .container {
      background: #fff;
      max-width: 500px;
      margin: auto;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    h2 {
      margin-bottom: 20px;
    }
    input, textarea, button {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    button {
      background: #333;
      color: #fff;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #555;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>🧠 AI Video Creator</h2>

    <h4>📄 Text to Video</h4>
    <textarea id="textInput" placeholder="Enter your script or idea..."></textarea>
    <button onclick="generateVideo()">Generate Video</button>

    <h4>🎬 YouTube to TikTok Clip</h4>
    <input id="youtubeInput" type="text" placeholder="Paste YouTube link...">
<button onclick="createClip()">Create Clip</button>
  </div>

  <script>
    function generateVideo() {
      const text = document.getElementById("textInput").value;
      if (!text.trim()) {
        alert("Please enter some text.");
        return;
      }
      alert("✅ AI is generating a video based on your text:\n\n" + text);
      // Here you can later add API call
    }

    function createClip() {
      const url = document.getElementById("youtubeInput").value;
      if (!url.trim()) {
        alert("Please enter a YouTube link.");
        return;
      }
      alert("🎬 Feature coming soon for YouTube shorts from:\n\n" + url);
      // Placeholder for clip editing tool/API
    }
  </script>
</body>
</html>
```
