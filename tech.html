# Bib-s-Hacker-Tech.<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Romantic Hacker Chat System</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap');
    * {
      transition: all 0.3s ease;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Share Tech Mono', monospace;
      background: url('https://files.catbox.moe/b2xl1t.jpg') no-repeat center center fixed;
      background-size: cover;
      filter: contrast(1);
      color: #0ff;
      height: 100vh;
      overflow: hidden;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    #loginScreen {
      position: absolute;
      width: 100%;
      height: 100%;
      z-index: 10;
      background: rgba(0,0,0,0.8);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    #loginScreen video {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    #loginScreen input, #loginScreen button {
      font-size: 1.2rem;
      padding: 12px 18px;
      margin: 10px;
      border: none;
      border-radius: 10px;
    }
    #loginScreen button {
      background-color: #ff69b4;
      color: #000;
      cursor: pointer;
    }
    .chat-container {
      background: rgba(0, 0, 0, 0.6);
      border: 2px solid #0ff;
      backdrop-filter: blur(6px);
      border-radius: 15px;
      padding: 20px;
      width: 95%;
      max-width: 1100px;
      height: 90vh;
      display: none;
      flex-direction: column;
      position: relative;
      z-index: 1;
    }
    h2 {
      text-align: center;
      color: #ff69b4;
      margin-bottom: 10px;
      font-size: 2rem;
    }
    .messages {
      flex: 1;
      overflow-y: auto;
      background: rgba(0, 0, 0, 0.4);
      border: 1px solid #0ff;
      border-radius: 10px;
      padding: 15px;
      margin-bottom: 15px;
    }
    .msg-block {
      margin-bottom: 15px;
      padding: 10px;
      background: rgba(0, 0, 20, 0.6);
      border-left: 4px solid #0ff;
      border-radius: 8px;
    }
    .sender-info {
      font-size: 12px;
      margin-bottom: 5px;
      color: #ff69b4;
    }
    .controls, .audio-controls, .links {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 15px;
      flex-wrap: wrap;
      margin-bottom: 10px;
    }
    .controls button, .audio-controls button, .links a {
      font-size: 1rem;
      padding: 12px 18px;
      border-radius: 10px;
      background-color: #0ff;
      color: #000;
      font-weight: bold;
      cursor: pointer;
      border: none;
    }
    .send-btn {
      background: #ff69b4;
    }
    footer {
      text-align: center;
      color: #ff69b4;
      font-size: 16px;
      padding-top: 10px;
    }
    audio { display: none; }
  </style>
</head>
<body>
  <div id="loginScreen">
    <video autoplay muted loop>
      <source src="https://files.catbox.moe/70j65p.mp4" type="video/mp4">
    </video>
    <input type="text" id="username" placeholder="Enter Username">
    <input type="password" id="password" placeholder="Enter Password">
    <button onclick="login()">Login</button>
  </div>  <audio id="bgMusic" loop>
    <source src="https://files.catbox.moe/y5q8aw.mp3" type="audio/mp3">
  </audio>  <div class="chat-container" id="chatContainer">
    <h2>💻 Romantic Hacker Chat</h2>
    <select id="friendSelect" onchange="loadChat()">
      <option value="reetah">💖 Reetah</option>
      <option value="khabib">🔥 Khabib</option>
      <option value="joy">💃 Joy</option>
      <option value="malia">🌸 Malia</option>
    </select><div class="messages" id="chatBox"></div>

<div class="controls">
  <input type="text" id="messageInput" placeholder="Type your message...">
  <button class="send-btn" onclick="sendMessage()">Send Message</button>
  <button onclick="showFlirt()">Flirt ❤️</button>
  <button onclick="logout()">Logout 🔒</button>
</div>

<div class="controls">
  <label>🎛️ Contrast</label>
  <input type="range" min="0.5" max="2" step="0.1" value="1" onchange="adjustContrast(this.value)">
</div>

<div class="audio-controls">
  <button onclick="playMusic()">▶️</button>
  <button onclick="pauseMusic()">⏸️</button>
  <button onclick="volumeUp()">🔊</button>
  <button onclick="volumeDown()">🔉</button>
  <button onclick="speakRecent()">🔈 Read</button>
</div>

<div class="links">
  <h3><a href="https://wa.me/254748950572" target="_blank">💬 WhatsApp</a></h3>
  <h3><a href="mailto:merabjoy01@gmail.com">📧 Email</a></h3>
</div>

<h2><footer>Mera-B System 💖</footer></h2>

  </div>  <script>
    const chatBox = document.getElementById('chatBox');
    const bgMusic = document.getElementById('bgMusic');
    const msgInput = document.getElementById('messageInput');
    const loginScreen = document.getElementById('loginScreen');
    const chatContainer = document.getElementById('chatContainer');

    function getKey(){ return 'chat_' + document.getElementById('friendSelect').value; }

    function loadChat(){
      chatBox.innerHTML = '';
      (JSON.parse(localStorage.getItem(getKey())) || []).forEach(msgObj => displayMsg(msgObj));
    }
    function saveChat(arr){ localStorage.setItem(getKey(), JSON.stringify(arr)); }

    function displayMsg({text, name, contact}){
      const block = document.createElement('div');
      block.className = 'msg-block';
      block.innerHTML = `<div class="sender-info">From: ${name || 'Anonymous'} | ${contact || ''}</div><div>${text}</div>`;
      chatBox.appendChild(block);
      chatBox.scrollTop = chatBox.scrollHeight;
    }

    function sendMessage(){
      let text = msgInput.value.trim();
      if (!text) return alert('Type a message!');
      const name = prompt('Sender name?', 'Anonymous');
      const contact = prompt('Contact?', '');
      const msgObj = {text, name, contact};
      const arr = JSON.parse(localStorage.getItem(getKey())) || [];
      arr.push(msgObj);
      saveChat(arr);
      displayMsg(msgObj);
      msgInput.value = '';
    }

    function speakRecent(){
      const arr = JSON.parse(localStorage.getItem(getKey())) || [];
      if (!arr.length) return;
      const {text, name} = arr[arr.length - 1];
      const msg = new SpeechSynthesisUtterance(`Message from ${name}: ${text}`);
      speechSynthesis.speak(msg);
    }

    function adjustContrast(v){ document.body.style.filter = `contrast(${v})`; }
    function playMusic(){ bgMusic.play(); }
    function pauseMusic(){ bgMusic.pause(); }
    function volumeUp(){ bgMusic.volume = Math.min(1, bgMusic.volume + 0.1); }
    function volumeDown(){ bgMusic.volume = Math.max(0, bgMusic.volume - 0.1); }

    function login(){
      const u = document.getElementById('username').value.trim();
      const p = document.getElementById('password').value.trim();
      if (u === 'Khabib' && p === '#Mera-b.Joy@01') {
        loginScreen.style.display = 'none';
        chatContainer.style.display = 'flex';
        bgMusic.volume = 0.5;
        bgMusic.play();
        loadChat();
      } else {
        alert('Wrong credentials!');
      }
    }

    function logout(){
      chatContainer.style.display = 'none';
      loginScreen.style.display = 'flex';
      document.getElementById('username').value = '';
      document.getElementById('password').value = '';
      bgMusic.pause();
    }

    function showFlirt(){
      fetch('https://api.quotable.io/random?tags=love')
        .then(res => res.json())
        .then(data => {
          const msg = `${data.content} — ${data.author}`;
          if(confirm(`${msg}\n\nCopy this message?`)){
            navigator.clipboard.writeText(msg);
          }
        })
        .catch(() => alert("Couldn't fetch flirt message. Try again."));
    }
  </script></body>
</html>
