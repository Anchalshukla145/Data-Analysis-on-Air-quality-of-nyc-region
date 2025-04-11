<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Air Quality Analysis – NYC</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f8f9fa;
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    h1, h2 {
      color: #1f4e79;
    }
    h1 {
      text-align: center;
      border-bottom: 2px solid #ccc;
      padding-bottom: 0.5rem;
    }
    .section {
      margin-bottom: 2rem;
    }
    ul {
      margin-left: 2rem;
    }
    code {
      background: #eee;
      padding: 2px 4px;
      border-radius: 4px;
    }
    .highlight {
      background-color: #e3f2fd;
      border-left: 5px solid #2196f3;
      padding: 1rem;
      margin: 1rem 0;
    }
    a {
      color: #0077cc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .footer {
      font-size: 0.9rem;
      color: #777;
      text-align: center;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <h1>🌫️ Air Quality Analysis – NYC</h1>

  <div class="section">
    <h2>📌 Project Overview</h2>
    <p>This project presents a deep dive into the air quality of New York City using real-world data. It includes data cleaning, exploration, and visual storytelling to understand the trends and patterns in air pollution.</p>
  </div>

  <div class="section">
    <h2>🧰 Tools & Technologies</h2>
    <ul>
      <li>Python</li>
      <li>Pandas</li>
      <li>Matplotlib</li>
      <li>Seaborn</li>
      <li>Jupyter Notebook</li>
    </ul>
  </div>

  <div class="section">
    <h2>📂 Dataset</h2>
    <p>Source: NYC Open Data via <a href="https://data.gov" target="_blank">Data.gov</a></p>
    <p>Download: <a href="https://data.cityofnewyork.us/api/views/c3uy-2p5r/rows.csv?accessType=DOWNLOAD" target="_blank">NYC Air Quality Dataset (CSV)</a></p>
    <p>This dataset includes pollutant readings like <strong>CO, NO2, O3, PM10</strong> from various monitoring stations across NYC.</p>
  </div>

  <div class="section">
    <h2>📈 Key Insights</h2>
    <ul>
      <li>PM10 and NO2 levels show seasonal fluctuation</li>
      <li>CO concentrations rise during winter months</li>
      <li>Strong correlations observed between specific pollutants</li>
    </ul>
  </div>

  <div class="section">
    <h2>🚧 Project Structure</h2>
    <pre>
Air_Quality_Analysis.ipynb   # Main Jupyter notebook
README.html                  # Project documentation
dataset/                     # (Optional) Folder for raw data
    </pre>
  </div>

  <div class="section">
    <h2>🧠 Skills Demonstrated</h2>
    <ul>
      <li>Data Cleaning & Preprocessing</li>
      <li>Exploratory Data Analysis (EDA)</li>
      <li>Data Visualization</li>
      <li>Real-World Dataset Handling</li>
      <li>Environmental Data Interpretation</li>
    </ul>
  </div>

  <div class="highlight">
    <strong>🔒 Disclaimer:</strong><br />
    This project was developed for academic and learning purposes only. The dataset and findings should not be used for policy-making or official decisions. Always consult certified environmental experts and validated data sources for critical applications.
  </div>

  <div class="section">
    <h2>📫 Contact</h2>
    <p>Feel free to connect with me on <a href="https://www.linkedin.com" target="_blank">LinkedIn</a> for feedback or collaboration!</p>
  </div>

  <div class="section">
    <h2>🔖 License</h2>
    <p>This project is released under the <a href="#">MIT License</a>.</p>
  </div>

  <div class="footer">
    © 2025 | Air Quality Analysis Project by Anchal
  </div>

</body>
</html>
