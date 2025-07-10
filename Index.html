<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PotholeSpotter - Demo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #1e88e5;
      color: white;
      padding: 1rem;
      display: flex;
      align-items: center;
    }
    header h1 {
      margin: 0 auto;
    }
    .menu-icon {
      cursor: pointer;
      padding: 0.5rem;
      font-size: 1.5rem;
      position: absolute;
      left: 1rem;
    }
    .sidebar {
      height: 100%;
      width: 250px;
      position: fixed;
      top: 0;
      left: -250px;
      background-color: #333;
      color: white;
      padding-top: 60px;
      transition: 0.3s;
      z-index: 1000;
    }
    .sidebar a {
      padding: 10px 20px;
      text-decoration: none;
      display: block;
      color: white;
      transition: 0.2s;
    }
    .sidebar a:hover {
      background-color: #575757;
    }
    .main-content {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .page {
      display: none;
    }
    .active {
      display: block;
    }
    .mockup {
      margin: 1rem 0;
      background-color: white;
      border-radius: 1rem;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .mockup img {
      width: 100%;
      border-radius: 0.5rem;
    }
    .tab-bar {
      display: flex;
      justify-content: space-around;
      background-color: #e0e0e0;
      position: fixed;
      bottom: 2.5rem;
      left: 0;
      width: 100%;
      padding: 1rem 0;
    }
    .tab-bar button {
      background: none;
      border: none;
      font-size: 1rem;
      cursor: pointer;
    }
    .mobile-buttons button,
    .mobile-small-buttons button {
      transition: transform 0.2s, background-color 0.2s;
    }
    .mobile-buttons button:hover,
    .mobile-small-buttons button:hover {
      background-color: #0d47a1;
      transform: scale(1.02);
    }
    .mobile-buttons button:active,
    .mobile-small-buttons button:active {
      background-color: #0a357a;
      transform: scale(0.98);
    }
    .mobile-buttons {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      margin-top: 2rem;
    }
    .mobile-buttons button {
      padding: 1rem;
      font-size: 1.2rem;
      background-color: #1565c0;
      color: white;
      border: none;
      border-radius: 0.5rem;
    }
    .mobile-small-buttons {
      display: flex;
      gap: 1rem;
      margin-top: 1rem;
    }
    .mobile-small-buttons button {
      flex: 1;
      padding: 0.75rem;
      font-size: 1rem;
      background-color: #42a5f5;
      color: white;
      border: none;
      border-radius: 0.5rem;
    }
    .nav-bar {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      background-color: #ccc;
      display: flex;
      justify-content: space-between;
      padding: 0.5rem 2rem;
    }
    .nav-bar button {
      font-size: 1.5rem;
      background: none;
      border: none;
      cursor: pointer;
    }
    .driving-page {
      display: none;
    }
    .driving-page.active {
      display: block;
    }
    .rounded-button {
      width: 100%;
      max-width: 300px;
      height: 150px;
      margin: 1rem auto;
      background-size: cover;
      background-position: center;
      color: white;
      font-size: 1.2rem;
      border: none;
      border-radius: 1rem;
      display: flex;
      justify-content: center;
      align-items: center;
    }
  </style>
</head>
<body>
  <header>
    <div class="menu-icon" onclick="toggleSidebar()">&#9776;</div>
    <h1>PotholeSpotter Vision Demo</h1>
  </header>

  <div class="sidebar" id="sidebar">
    <a href="#" onclick="showPage('backend')">Backend</a>
    <a href="#" onclick="showPage('mobile')">Mobile Interface</a>
  </div>

  <div class="main-content">
    <section id="backend" class="page">
      <h2>Backend Interface</h2>
      <div class="mockup" id="backend-content">
        <h3>Traffic (Default)</h3>
        <img src="https://via.placeholder.com/800x400?text=Live+Traffic+Connections" alt="Traffic Data">
      </div>
    </section>

    <section id="mobile" class="page">
      <h2>Mobile App Home Screen</h2>
      <div class="mobile-buttons">
        <button onclick="showDrivingPage()">Start Driving</button>
        <button>Report Pothole</button>
        <button>View Nearby</button>
      </div>
      <div class="mobile-small-buttons">
        <button>Calibrate</button>
        <button>Settings</button>
      </div>
    </section>

    <section id="driving" class="driving-page">
      <h2>Driving Mode</h2>
      <!-- Ad Placeholder -->
      <div class="mockup">
        <p style="text-align: center; color: gray;">[Ad Banner Placeholder]</p>
      </div>
      <!-- MAP button with background image -->
      <button class="rounded-button" style="background-image: url('https://via.placeholder.com/300x150?text=Google+Maps');">
        MAP
        <!-- TODO: Replace with actual Google Maps icon/image -->
      </button>
      <!-- Select Destination button -->
      <button class="rounded-button" style="background-image: url('https://via.placeholder.com/300x150?text=Destination+Map');">
        Select Destination
        <!-- TODO: Replace with actual navigation icon -->
      </button>
      <!-- Secure Phone button -->
      <button class="rounded-button" style="background-image: url('https://via.placeholder.com/300x150?text=Secure+Phone');">
        Secure Phone
        <!-- TODO: Replace with actual secure lock image -->
      </button>
    </section>
  </div>

  <div class="tab-bar" id="backend-tabs" style="display: none;">
    <button onclick="changeBackendTab('Traffic')">Traffic</button>
    <button onclick="changeBackendTab('Pending')">Pending Reports</button>
    <button onclick="changeBackendTab('Reports')">Pothole Reports</button>
  </div>

  <!-- Global Navigation Buttons -->
  <div class="nav-bar">
    <button onclick="navigateBack()">&#8592;</button>
    <button onclick="navigateNext()">&#8594;</button>
  </div>

  <script>
    function toggleSidebar() {
      const sidebar = document.getElementById("sidebar");
      sidebar.style.left = sidebar.style.left === "0px" ? "-250px" : "0px";
    }

    function showPage(id) {
      document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
      document.querySelectorAll('.driving-page').forEach(p => p.classList.remove('active'));
      document.getElementById(id).classList.add('active');
      document.getElementById("sidebar").style.left = "-250px";
      document.getElementById("backend-tabs").style.display = id === "backend" ? "flex" : "none";
    }

    function showDrivingPage() {
      document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
      document.querySelectorAll('.driving-page').forEach(p => p.classList.remove('active'));
      document.getElementById("driving").classList.add('active');
    }

    function changeBackendTab(tab) {
      const backendContent = document.getElementById("backend-content");
      if (tab === 'Traffic') {
        backendContent.innerHTML = `
          <h3>Traffic</h3>
          <img src="https://via.placeholder.com/800x400?text=Live+Traffic+Connections" alt="Traffic Data">
        `;
      } else if (tab === 'Pending') {
        backendContent.innerHTML = `
          <h3>Pending Reports</h3>
          <img src="https://via.placeholder.com/800x400?text=Pending+Mobile+Reports" alt="Pending Reports">
        `;
      } else if (tab === 'Reports') {
        backendContent.innerHTML = `
          <h3>Pothole Reports</h3>
          <img src="https://via.placeholder.com/800x400?text=Stored+Pothole+Reports" alt="Pothole Reports">
        `;
      }
    }

    // Navigation placeholders — for future screen linking
    function navigateBack() {
      alert("Back navigation clicked (to be implemented)");
    }
    function navigateNext() {
      alert("Next navigation clicked (to be implemented)");
    }
  </script>
</body>
</html>
