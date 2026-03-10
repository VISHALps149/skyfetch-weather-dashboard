<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SkyFetch Weather Dashboard</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    <h1>SkyFetch Weather Dashboard</h1>

    <div class="search-box">
      <input type="text" id="cityInput" placeholder="Enter city name">
      <button id="searchBtn">Search</button>
    </div>

    <div class="weather-card" id="weatherResult">
      <h2 id="cityName"></h2>
      <p id="temperature"></p>
      <p id="humidity"></p>
      <p id="condition"></p>
    </div>

    <div class="recent">
      <h3>Recent Searches</h3>
      <ul id="recentList"></ul>
    </div>
  </div>

  <script src="script.js"></script>

</body>
</html>
