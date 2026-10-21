<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Meri Yaadein - Shared Diary & Chat</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- Firebase SDKs -->
  <script src="https://www.gstatic.com/firebasejs/9.22.1/firebase-app-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/9.22.1/firebase-firestore-compat.js"></script>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      -webkit-tap-highlight-color: transparent;
    }

    html, body {
      background-color: #f8fafc;
      color: #1e293b;
      min-height: 100%;
      overflow-x: hidden;
    }

    body {
      padding: 14px 12px 100px 12px;
    }

    .container {
      max-width: 480px;
      margin: 0 auto;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 16px;
    }

    .brand-wrap {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo-badge {
      width: 44px;
      height: 44px;
      background: linear-gradient(135deg, #ff7a18, #ff3f5e);
      border-radius: 14px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #ffffff;
      font-size: 1.25rem;
      box-shadow: 0 4px 10px rgba(255, 63, 94, 0.3);
    }

    .brand-text h1 {
      font-size: 1.2rem;
      font-weight: 700;
      color: #0f172a;
    }

    .brand-text p {
      font-size: 0.7rem;
      color: #94a3b8;
      text-transform: uppercase;
      font-weight: 600;
    }

    .counter-pill {
      background: #ffe4e6;
      color: #e11d48;
      padding: 6px 12px;
      border-radius: 20px;
      font-size: 0.78rem;
      font-weight: 600;
      display: flex;
      align-items: center;
      gap: 5px;
    }

    /* Secret Exchange Code Card */
    .exchange-card {
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-radius: 18px;
      padding: 14px;
      margin-bottom: 18px;
      box-shadow: 0 3px 12px rgba(0,0,0,0.04);
    }

    .active-code-banner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background: #f0fdf4;
      border: 1.5px dashed #22c55e;
      padding: 10px 14px;
      border-radius: 14px;
      margin-bottom: 12px;
    }

    .active-code-info span {
      font-size: 0.7rem;
      color: #15803d;
      font-weight: 700;
      text-transform: uppercase;
      display: block;
    }

    .active-code-info strong {
      font-size: 1.35rem;
      color: #166534;
      letter-spacing: 2px;
    }

    .gen-new-btn {
      background: #22c55e;
      color: #fff;
      border: none;
      padding: 8px 12px;
      border-radius: 10px;
      font-size: 0.75rem;
      font-weight: 700;
      cursor: pointer;
    }

    .join-row {
      display: flex;
      gap: 8px;
    }

    .code-input {
      flex: 1;
      padding: 10px 14px;
      background: #f8fafc;
      border: 1px solid #cbd5e1;
      border-radius: 12px;
      font-size: 0.95rem;
      font-weight: 700;
      letter-spacing: 1.5px;
      outline: none;
      text-align: center;
    }

    .join-btn {
      background: #0284c7;
      color: #fff;
      border: none;
      padding: 10px 16px;
      border-radius: 12px;
      font-size: 0.82rem;
      font-weight: 700;
      cursor: pointer;
    }

    .room-history-wrap {
      display: flex;
      align-items: center;
      gap: 6px;
      margin-top: 10px;
      overflow-x: auto;
      scrollbar-width: none;
    }

    .room-history-wrap::-webkit-scrollbar {
      display: none;
    }

    .history-title {
      font-size: 0.68rem;
      font-weight: 700;
      color: #94a3b8;
      text-transform: uppercase;
      white-space: nowrap;
    }

    .room-chip {
      background: #f1f5f9;
      color: #334155;
      padding: 4px 10px;
      border-radius: 10px;
      font-size: 0.75rem;
      font-weight: 700;
      white-space: nowrap;
      cursor: pointer;
      border: 1px solid #e2e8f0;
    }

    .room-chip.active {
      background: #dbeafe;
      color: #1d4ed8;
      border-color: #3b82f6;
    }

    /* Upload Box */
    .create-card {
      background: #ffffff;
      border-radius: 20px;
      padding: 16px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
      border: 1px solid #f1f5f9;
      margin-bottom: 22px;
    }

    .card-title-row {
      display: flex;
      align-items: center;
      gap: 8px;
      margin-bottom: 12px;
    }

    .dot-indicator {
      width: 8px;
      height: 8px;
      background: #f43f5e;
      border-radius: 50%;
    }

    .card-title-row h2 {
      font-size: 0.85rem;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      color: #334155;
      font-weight: 700;
    }

    .picker-options {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      margin-bottom: 12px;
    }

    .picker-btn {
      background: #f8fafc;
      border: 1.5px dashed #cbd5e1;
      border-radius: 14px;
      padding: 14px 10px;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 6px;
      cursor: pointer;
      color: #334155;
      font-size: 0.85rem;
      font-weight: 600;
    }

    #previewBox {
      display: none;
      position: relative;
      margin-bottom: 14px;
      background: #f1f5f9;
      padding: 10px;
      border-radius: 14px;
    }

    .preview-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 8px;
      max-height: 220px;
      overflow-y: auto;
    }

    .preview-thumb-wrap {
      width: 100%;
      height: 75px;
      border-radius: 8px;
      overflow: hidden;
    }

    .preview-thumb-wrap img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .cancel-preview {
      position: absolute;
      top: -6px;
      right: -6px;
      background: #ef4444;
      color: #fff;
      border: 2px solid #fff;
      width: 26px;
      height: 26px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      z-index: 5;
    }

    .field-group {
      margin-bottom: 12px;
    }

    .field-label {
      font-size: 0.76rem;
      font-weight: 600;
      color: #64748b;
      margin-bottom: 5px;
      display: block;
    }

    .custom-input, .custom-select {
      width: 100%;
      padding: 12px 14px;
      background: #f8fafc;
      border: 1px solid #e2e8f0;
      border-radius: 12px;
      color: #1e293b;
      font-size: 0.9rem;
      outline: none;
    }

    .form-row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      margin-bottom: 16px;
    }

    .save-button {
      width: 100%;
      background: linear-gradient(135deg, #f43f5e, #e11d48);
      color: #ffffff;
      border: none;
      padding: 14px;
      border-radius: 14px;
      font-size: 0.95rem;
      font-weight: 700;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      box-shadow: 0 6px 18px rgba(244, 63, 94, 0.35);
    }

    /* Filter Tabs */
    .filter-scroll {
      display: flex;
      gap: 8px;
      overflow-x: auto;
      padding-bottom: 10px;
      margin-bottom: 12px;
      scrollbar-width: none;
    }

    .filter-scroll::-webkit-scrollbar {
      display: none;
    }

    .filter-btn {
      padding: 7px 14px;
      border-radius: 20px;
      font-size: 0.78rem;
      font-weight: 600;
      white-space: nowrap;
      border: 1px solid #e2e8f0;
      background: #ffffff;
      color: #64748b;
      cursor: pointer;
    }

    .filter-btn.active {
      background: #f43f5e;
      color: #ffffff;
      border-color: #f43f5e;
    }

    /* Timeline Cards */
    .timeline-list {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    .memory-card {
      background: #ffffff;
      border-radius: 18px;
      overflow: hidden;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.04);
      border: 1px solid #f1f5f9;
    }

    .memory-image-container {
      position: relative;
      width: 100%;
      height: 220px;
      cursor: pointer;
    }

    .memory-image-container img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    .tag-badge {
      position: absolute;
      top: 10px;
      left: 10px;
      background: rgba(15, 23, 42, 0.7);
      backdrop-filter: blur(4px);
      color: #ffffff;
      padding: 4px 10px;
      border-radius: 16px;
      font-size: 0.72rem;
      font-weight: 500;
    }

    .memory-details {
      padding: 12px 14px;
    }

    .memory-caption {
      font-size: 0.92rem;
      color: #1e293b;
      font-weight: 500;
      line-height: 1.4;
      margin-bottom: 10px;
    }

    .memory-bottom-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-top: 1px solid #f8fafc;
      padding-top: 8px;
    }

    .actions-left {
      display: flex;
      align-items: center;
      gap: 14px;
    }

    .action-icon-btn {
      background: none;
      border: none;
      font-size: 1.15rem;
      color: #94a3b8;
      cursor: pointer;
      text-decoration: none;
      display: flex;
      align-items: center;
    }

    .action-icon-btn.liked {
      color: #e11d48;
    }

    .memory-date {
      font-size: 0.75rem;
      color: #94a3b8;
      display: flex;
      align-items: center;
      gap: 4px;
    }

    .delete-action-btn {
      background: #fef2f2;
      border: 1px solid #fecaca;
      color: #ef4444;
      padding: 5px 10px;
      border-radius: 8px;
      font-size: 0.75rem;
      font-weight: 600;
      cursor: pointer;
    }

    .empty-box {
      text-align: center;
      padding: 30px 10px;
      color: #94a3b8;
      font-size: 0.85rem;
    }

    /* Floating Chat */
    .floating-chat-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      width: 56px;
      height: 56px;
      border-radius: 50%;
      background: linear-gradient(135deg, #0284c7, #2563eb);
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.4rem;
      box-shadow: 0 6px 20px rgba(37, 99, 235, 0.4);
      cursor: pointer;
      z-index: 1000;
      border: none;
    }

    .chat-drawer {
      display: none;
      position: fixed;
      inset: 0;
      background: rgba(0,0,0,0.5);
      z-index: 10000;
      justify-content: flex-end;
      flex-direction: column;
    }

    .chat-box {
      background: #ffffff;
      width: 100%;
      height: 75vh;
      border-radius: 24px 24px 0 0;
      display: flex;
      flex-direction: column;
      overflow: hidden;
    }

    .chat-header {
      background: #0284c7;
      color: #ffffff;
      padding: 16px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .chat-messages {
      flex: 1;
      padding: 14px;
      overflow-y: auto;
      display: flex;
      flex-direction: column;
      gap: 10px;
      background: #f1f5f9;
    }

    .chat-msg {
      max-width: 80%;
      padding: 8px 12px;
      border-radius: 14px;
      font-size: 0.88rem;
      word-break: break-word;
    }

    .chat-msg.me {
      align-self: flex-end;
      background: #0284c7;
      color: #ffffff;
      border-bottom-right-radius: 4px;
    }

    .chat-msg.them {
      align-self: flex-start;
      background: #ffffff;
      color: #1e293b;
      border-bottom-left-radius: 4px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.06);
    }

    .chat-sender {
      font-size: 0.68rem;
      font-weight: 700;
      margin-bottom: 2px;
      opacity: 0.85;
    }

    .chat-input-bar {
      display: flex;
      padding: 10px;
      background: #ffffff;
      border-top: 1px solid #e2e8f0;
      gap: 8px;
    }

    .chat-input-bar input {
      flex: 1;
      padding: 10px 14px;
      border-radius: 20px;
      border: 1px solid #cbd5e1;
      outline: none;
      font-size: 0.9rem;
    }

    .chat-send-btn {
      width: 42px;
      height: 42px;
      background: #0284c7;
      color: #fff;
      border: none;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <div class="container">
    <header>
      <div class="brand-wrap">
        <div class="logo-badge"><i class="fa-solid fa-camera"></i></div>
        <div class="brand-text">
          <h1>Meri Yaadein</h1>
          <p>Instant Shared Code Connect</p>
        </div>
      </div>
      <div class="counter-pill">
        <i class="fa-solid fa-heart"></i> <span id="photoCount">0 Photos</span>
      </div>
    </header>

    <!-- Code Sync Box -->
    <div class="exchange-card">
      <div class="active-code-banner">
        <div class="active-code-info">
          <span>Active Code (Sync)</span>
          <strong id="displayActiveCode">----</strong>
        </div>
        <button class="gen-new-btn" id="generateCodeBtn"><i class="fa-solid fa-rotate"></i> Naya Code</button>
      </div>

      <div class="join-row">
        <input type="text" id="joinCodeInput" class="code-input" placeholder="Dost ka Code daalein" maxlength="8">
        <button class="join-btn" id="joinCodeBtn">Sync Karein</button>
      </div>

      <div class="room-history-wrap">
        <span class="history-title">Recent:</span>
        <div id="chipsContainer" style="display: flex; gap: 6px;"></div>
      </div>
    </div>

    <!-- Upload Card -->
    <section class="create-card">
      <div class="card-title-row">
        <span class="dot-indicator"></span>
        <h2>Nayi Yaadein Jodein</h2>
      </div>

      <input type="file" id="cameraInput" accept="image/*" capture="environment" style="display:none;">
      <input type="file" id="galleryInput" accept="image/*" multiple style="display:none;">

      <div class="picker-options" id="pickerContainer">
        <div class="picker-btn" onclick="document.getElementById('cameraInput').click()">
          <i class="fa-solid fa-camera" style="color: #f43f5e; font-size:1.4rem;"></i>
          <span>Camera</span>
        </div>
        <div class="picker-btn" onclick="document.getElementById('galleryInput').click()">
          <i class="fa-solid fa-images" style="color: #0284c7; font-size:1.4rem;"></i>
          <span>Gallery</span>
        </div>
      </div>

      <div id="previewBox">
        <button type="button" class="cancel-preview" id="cancelImg"><i class="fa-solid fa-xmark"></i></button>
        <div class="preview-grid" id="previewGrid"></div>
      </div>

      <div class="field-group">
        <label class="field-label">Caption ya Kahani</label>
        <input type="text" id="captionText" class="custom-input" placeholder="Jaise: Doston ke sath party... ✨">
      </div>

      <div class="form-row">
        <div>
          <label class="field-label">Tareekh</label>
          <input type="date" id="dateInput" class="custom-input">
        </div>
        <div>
          <label class="field-label">Category / Tag</label>
          <select id="tagSelect" class="custom-select">
            <option value="Dost">👥 Dost (Friends)</option>
            <option value="Parivar">🏠 Parivar (Family)</option>
            <option value="Safar">✈️ Safar (Travel)</option>
            <option value="Personal">🌟 Personal</option>
          </select>
        </div>
      </div>

      <button type="button" class="save-button" id="saveActionBtn">
        <i class="fa-solid fa-cloud-arrow-up"></i> Photos Share Karein
      </button>
    </section>

    <!-- Filter Tabs -->
    <div class="filter-scroll">
      <button class="filter-btn active" data-filter="all">Sabhi</button>
      <button class="filter-btn" data-filter="Dost">👥 Dost</button>
      <button class="filter-btn" data-filter="Parivar">🏠 Parivar</button>
      <button class="filter-btn" data-filter="Safar">✈️ Safar</button>
      <button class="filter-btn" data-filter="Personal">🌟 Personal</button>
    </div>

    <!-- Timeline List -->
    <section>
      <div class="timeline-list" id="timelineList"></div>
    </section>
  </div>

  <!-- Floating Chat Button -->
  <button class="floating-chat-btn" id="openChatBtn" title="Instant Chat">
    <i class="fa-solid fa-comments"></i>
  </button>

  <!-- Chat Drawer -->
  <div class="chat-drawer" id="chatDrawer">
    <div class="chat-box">
      <div class="chat-header">
        <div>
          <h3>Room Chat</h3>
          <span style="font-size:0.75rem; opacity:0.85;" id="chatRoomName">Connected: ----</span>
        </div>
        <button style="background:none; border:none; color:#fff; font-size:1.3rem; cursor:pointer;" id="closeChatBtn">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>

      <div class="chat-messages" id="chatMessages">
        <div style="text-align:center; color:#94a3b8; font-size:0.8rem; margin:auto;">Code exchange karke baatein shuru karein! 👋</div>
      </div>

      <div class="chat-input-bar">
        <input type="text" id="chatInput" placeholder="Message likhein...">
        <button class="chat-send-btn" id="sendMsgBtn"><i class="fa-solid fa-paper-plane"></i></button>
      </div>
    </div>
  </div>

  <script>
    const firebaseConfig = {
      apiKey: "AIzaSyD1GsDYdK8bwS7X-2FD_HFS2vI_tocCLwQ",
      authDomain: "meri-yaadein.firebaseapp.com",
      projectId: "meri-yaadein",
      storageBucket: "meri-yaadein.firebasestorage.app",
      messagingSenderId: "627746655795",
      appId: "1:627746655795:web:164bde8f79ae54e59f5d46"
    };

    firebase.initializeApp(firebaseConfig);
    const db = firebase.firestore();

    let myUserId = localStorage.getItem("my_user_id") || "user_" + Math.random().toString(36).substr(2, 6);
    localStorage.setItem("my_user_id", myUserId);

    let myUserName = localStorage.getItem("my_chat_name") || "";

    function createRandomCode() {
      return Math.floor(1000 + Math.random() * 9000).toString();
    }

    let currentRoom = localStorage.getItem("active_secret_code");
    if (!currentRoom) {
      currentRoom = createRandomCode();
      localStorage.setItem("active_secret_code", currentRoom);
    }

    let currentFilter = 'all';
    let unsubscribeMemories = null;
    let unsubscribeChat = null;
    let allMemoriesData = [];

    const displayActiveCode = document.getElementById("displayActiveCode");
    const generateCodeBtn = document.getElementById("generateCodeBtn");
    const joinCodeInput = document.getElementById("joinCodeInput");
    const joinCodeBtn = document.getElementById("joinCodeBtn");
    const chatRoomName = document.getElementById("chatRoomName");
    const chipsContainer = document.getElementById("chipsContainer");
    const timelineList = document.getElementById("timelineList");
    const photoCount = document.getElementById("photoCount");

    function updateActiveCodeUI(code) {
      displayActiveCode.textContent = code;
      chatRoomName.textContent = "Connected: " + code;
      saveCodeToRecent(code);
      listenToRoom(code);
    }

    function saveCodeToRecent(code) {
      let list = JSON.parse(localStorage.getItem("recent_codes_list") || "[]");
      if (!list.includes(code)) {
        list.unshift(code);
        if (list.length > 5) list.pop();
        localStorage.setItem("recent_codes_list", JSON.stringify(list));
      }
      renderCodeChips();
    }

    function renderCodeChips() {
      let list = JSON.parse(localStorage.getItem("recent_codes_list") || "[]");
      chipsContainer.innerHTML = "";
      list.forEach(c => {
        const chip = document.createElement("span");
        chip.className = `room-chip ${c === currentRoom ? 'active' : ''}`;
        chip.textContent = `#${c}`;
        chip.addEventListener("click", () => {
          currentRoom = c;
          localStorage.setItem("active_secret_code", currentRoom);
          updateActiveCodeUI(currentRoom);
        });
        chipsContainer.appendChild(chip);
      });
    }

    generateCodeBtn.addEventListener("click", () => {
      currentRoom = createRandomCode();
      localStorage.setItem("active_secret_code", currentRoom);
      updateActiveCodeUI(currentRoom);
    });

    joinCodeBtn.addEventListener("click", () => {
      const code = joinCodeInput.value.trim();
      if (!code) return alert("Code likhein!");
      currentRoom = code;
      localStorage.setItem("active_secret_code", currentRoom);
      joinCodeInput.value = "";
      updateActiveCodeUI(currentRoom);
    });

    // Compression & Bulk Upload
    const cameraInput = document.getElementById("cameraInput");
    const galleryInput = document.getElementById("galleryInput");
    const pickerContainer = document.getElementById("pickerContainer");
    const previewBox = document.getElementById("previewBox");
    const previewGrid = document.getElementById("previewGrid");
    const cancelImg = document.getElementById("cancelImg");
    const captionText = document.getElementById("captionText");
    const dateInput = document.getElementById("dateInput");
    const tagSelect = document.getElementById("tagSelect");
    const saveActionBtn = document.getElementById("saveActionBtn");

    dateInput.valueAsDate = new Date();
    let compressedImagesList = [];

    function compressFile(file) {
      return new Promise((resolve) => {
        const reader = new FileReader();
        reader.onload = function(e) {
          const img = new Image();
          img.onload = function() {
            const canvas = document.createElement("canvas");
            const MAX_WIDTH = 600;
            let width = img.width;
            let height = img.height;
            if (width > MAX_WIDTH) {
              height = (height * MAX_WIDTH) / width;
              width = MAX_WIDTH;
            }
            canvas.width = width;
            canvas.height = height;
            const ctx = canvas.getContext("2d");
            ctx.drawImage(img, 0, 0, width, height);
            resolve(canvas.toDataURL("image/jpeg", 0.55));
          };
          img.src = e.target.result;
        };
        reader.readAsDataURL(file);
      });
    }

    async function processFiles(fileList) {
      if (!fileList || fileList.length === 0) return;
      saveActionBtn.disabled = true;
      saveActionBtn.innerHTML = '<i class="fa-solid fa-spinner fa-spin"></i> Processing...';

      for (let i = 0; i < fileList.length; i++) {
        const base64 = await compressFile(fileList[i]);
        compressedImagesList.push(base64);
      }

      renderPreviews();
      saveActionBtn.disabled = false;
      saveActionBtn.innerHTML = `<i class="fa-solid fa-cloud-arrow-up"></i> ${compressedImagesList.length} Photos Share Karein`;
    }

    function renderPreviews() {
      if (compressedImagesList.length === 0) {
        previewBox.style.display = "none";
        pickerContainer.style.display = "grid";
        saveActionBtn.innerHTML = '<i class="fa-solid fa-cloud-arrow-up"></i> Photos Share Karein';
        return;
      }
      previewGrid.innerHTML = "";
      compressedImagesList.forEach(src => {
        const thumb = document.createElement("div");
        thumb.className = "preview-thumb-wrap";
        thumb.innerHTML = `<img src="${src}" alt="Preview">`;
        previewGrid.appendChild(thumb);
      });
      previewBox.style.display = "block";
      pickerContainer.style.display = "none";
    }

    cameraInput.addEventListener("change", function() { processFiles(this.files); });
    galleryInput.addEventListener("change", function() { processFiles(this.files); });

    cancelImg.addEventListener("click", () => {
      compressedImagesList = [];
      cameraInput.value = "";
      galleryInput.value = "";
      renderPreviews();
    });

    saveActionBtn.addEventListener("click", async () => {
      if (compressedImagesList.length === 0) return alert("Pehle gallery ya camera se photos select karein!");
      saveActionBtn.disabled = true;
      const total = compressedImagesList.length;
      const caption = captionText.value.trim() || "Meri Ek Pyari Yaad";
      const selectedDate = dateInput.value || new Date().toISOString().split('T')[0];
      const tag = tagSelect.value;

      try {
        for (let i = 0; i < total; i++) {
          saveActionBtn.innerHTML = `<i class="fa-solid fa-spinner fa-spin"></i> Uploading ${i + 1}/${total}...`;
          await db.collection("rooms").doc(currentRoom).collection("memories").add({
            image: compressedImagesList[i],
            caption: total > 1 ? `${caption} (${i + 1})` : caption,
            date: selectedDate,
            tag: tag,
            isLiked: false,
            created: Date.now() + i
          });
        }
        captionText.value = "";
        compressedImagesList = [];
        cameraInput.value = "";
        galleryInput.value = "";
        renderPreviews();
      } catch (err) {
        alert("Upload fail! " + err.message);
      } finally {
        saveActionBtn.disabled = false;
        saveActionBtn.innerHTML = '<i class="fa-solid fa-cloud-arrow-up"></i> Photos Share Karein';
      }
    });

    // Realtime Listener
    function listenToRoom(room) {
      if (unsubscribeMemories) unsubscribeMemories();
      if (unsubscribeChat) unsubscribeChat();

      timelineList.innerHTML = '<div class="empty-box">Connecting & Syncing... ⏳</div>';

      unsubscribeMemories = db.collection("rooms").doc(room).collection("memories")
        .orderBy("created", "desc")
        .onSnapshot(snapshot => {
          allMemoriesData = [];
          snapshot.forEach(doc => allMemoriesData.push({ id: doc.id, ...doc.data() }));
          renderFilteredList();
        });

      unsubscribeChat = db.collection("rooms").doc(room).collection("chats")
        .orderBy("timestamp", "asc")
        .onSnapshot(snapshot => {
          const chatMessages = document.getElementById("chatMessages");
          chatMessages.innerHTML = "";
          if (snapshot.empty) {
            chatMessages.innerHTML = '<div style="text-align:center; color:#94a3b8; font-size:0.8rem; margin:auto;">Code exchange karke baatein shuru karein! 👋</div>';
            return;
          }
          snapshot.forEach(doc => {
            const data = doc.data();
            const msgDiv = document.createElement("div");
            const isMe = data.senderId === myUserId;
            msgDiv.className = `chat-msg ${isMe ? 'me' : 'them'}`;
            msgDiv.innerHTML = `
              <div class="chat-sender">${escapeHtml(data.senderName || (isMe ? 'Main' : 'Dost'))}</div>
              <div>${escapeHtml(data.text)}</div>
            `;
            chatMessages.appendChild(msgDiv);
          });
          chatMessages.scrollTop = chatMessages.scrollHeight;
        });
    }

    function renderFilteredList() {
      timelineList.innerHTML = "";
      photoCount.textContent = `${allMemoriesData.length} Photos`;

      let filtered = (currentFilter === 'all') 
        ? allMemoriesData 
        : allMemoriesData.filter(m => m.tag === currentFilter);

      if (filtered.length === 0) {
        timelineList.innerHTML = '<div class="empty-box">Is category me abhi koi photo nahi hai. Upar se upload karein! ✨</div>';
        return;
      }

      filtered.forEach(item => {
        const card = document.createElement("div");
        card.className = "memory-card";
        card.innerHTML = `
          <div class="memory-image-container">
            <span class="tag-badge"><i class="fa-solid fa-tag"></i> ${item.tag || 'Personal'}</span>
            <img src="${item.image}" alt="Photo" loading="lazy">
          </div>
          <div class="memory-details">
            <div class="memory-caption">${escapeHtml(item.caption || '')}</div>
            <div class="memory-bottom-row">
              <div class="actions-left">
                <button class="action-icon-btn ${item.isLiked ? 'liked' : ''}" onclick="toggleLike('${item.id}', ${item.isLiked})" title="Like">
                  <i class="${item.isLiked ? 'fa-solid' : 'fa-regular'} fa-heart"></i>
                </button>
                <a href="${item.image}" download="photo.jpg" class="action-icon-btn" title="Phone me save karein">
                  <i class="fa-solid fa-download"></i>
                </a>
                <span class="memory-date"><i class="fa-regular fa-calendar"></i> ${item.date || ''}</span>
              </div>
              <button class="delete-action-btn" onclick="removePhoto('${item.id}')">Hataayein</button>
            </div>
          </div>
        `;
        timelineList.appendChild(card);
      });
    }

    window.toggleLike = function(id, status) {
      db.collection("rooms").doc(currentRoom).collection("memories").doc(id).update({
        isLiked: !status
      });
    };

    window.removePhoto = function(id) {
      if (confirm("Kya aap is photo ko delete karna chahte hain?")) {
        db.collection("rooms").doc(currentRoom).collection("memories").doc(id).delete();
      }
    };

    document.querySelectorAll('.filter-btn').forEach(btn => {
      btn.addEventListener('click', function() {
        document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
        this.classList.add('active');
        currentFilter = this.getAttribute('data-filter');
        renderFilteredList();
      });
    });

    // Chat Drawer
    const openChatBtn = document.getElementById("openChatBtn");
    const closeChatBtn = document.getElementById("closeChatBtn");
    const chatDrawer = document.getElementById("chatDrawer");
    const chatInput = document.getElementById("chatInput");
    const sendMsgBtn = document.getElementById("sendMsgBtn");

    openChatBtn.addEventListener("click", () => {
      if (!myUserName) {
        let name = prompt("Chat ke liye apna naam likhein:");
        myUserName = (name && name.trim()) ? name.trim() : "User";
        localStorage.setItem("my_chat_name", myUserName);
      }
      chatDrawer.style.display = "flex";
      const cm = document.getElementById("chatMessages");
      cm.scrollTop = cm.scrollHeight;
    });

    closeChatBtn.addEventListener("click", () => { chatDrawer.style.display = "none"; });
    chatDrawer.addEventListener("click", (e) => { if (e.target === chatDrawer) chatDrawer.style.display = "none"; });

    async function sendMessage() {
      const text = chatInput.value.trim();
      if (!text) return;
      chatInput.value = "";
      try {
        await db.collection("rooms").doc(currentRoom).collection("chats").add({
          text: text,
          senderId: myUserId,
          senderName: myUserName || "Main",
          timestamp: Date.now()
        });
      } catch (e) {
        console.error("Chat send failed", e);
      }
    }

    sendMsgBtn.addEventListener("click", sendMessage);
    chatInput.addEventListener("keypress", (e) => { if (e.key === "Enter") sendMessage(); });

    function escapeHtml(str) {
      return str.replace(/[&<>"']/g, m => ({ '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#039;' })[m]);
    }

    updateActiveCodeUI(currentRoom);
  </script>
</body>
</html>
