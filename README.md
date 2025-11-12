<div style="font-family: 'Times New Roman', Times, serif; line-height: 1.5;">

<h1><strong>Project: Analyzing and Visualizing the World's Top Billionaires 2024</strong></h1>

<ol>
  <li><strong>Objective</strong>
    <ol type="">
      <li>Understand patterns in global billionaire distribution.</li>
      <li>Identify key factors associated with high net worth.</li>
      <li>Build and compare predictive models for billionaire net worth.</li>
    </ol>
  </li>

  <li><strong>Introduction</strong>
    <p>The world’s billionaires hold immense influence over the global economy. This project analyzes a 2024 sample dataset of the world’s richest individuals to explore wealth distribution by country, industry, and source of income, and to predict net worth using machine learning models.
    The analysis is conducted using Python in Google Colab, focusing on data exploration, visualization, and regression modeling.</p>
  </li>

  <li><strong>Data Preparation</strong>
    <p>A custom dataset of 20 billionaires was created containing the following attributes:</p>
    <ul>
      <li>Rank</li>
      <li>Name</li>
      <li>Net Worth (in billions USD)</li>
      <li>Age</li>
      <li>Gender</li>
      <li>Country</li>
      <li>Industry</li>
      <li>Source of Wealth</li>
    </ul>
    <p>Data cleaning included:</p>
    <ul>
      <li>Handling missing values and duplicates</li>
      <li>Ensuring correct data types</li>
      <li>Creating new analytical features such as AgeGroup, WealthGroup, and IsSelfMade</li>
    </ul>
  </li>

  <li><strong>Exploratory Data Analysis (EDA)</strong>
    <p>Visualizations were used to gain insights into billionaire demographics and wealth patterns:</p>
    <ul>
      <li>Top Countries by billionaire count</li>
      <li>Net Worth Distribution across individuals</li>
      <li>Industries by Total Wealth</li>
      <li>Age vs Net Worth correlation</li>
      <li>Wealth Sources (Pie Chart)</li>
      <li>Gender Distribution (Pie Chart)</li>
    </ul>
    <p><strong>Key Findings:</strong></p>
    <ul>
      <li>The United States dominates in both number and total wealth of billionaires.</li>
      <li>The Technology industry leads in accumulated net worth.</li>
      <li>Self-made billionaires account for the majority of the top 20 list.</li>
      <li>Male billionaires significantly outnumber females in this dataset.</li>
    </ul>
  </li>

  <li><strong>Feature Engineering &amp; Modeling</strong>
    <p><strong>Engineered features:</strong></p>
    <ul>
      <li>AgeGroup (Young, Middle-aged, Senior)</li>
      <li>WealthGroup (Medium, High, Ultra-High)</li>
      <li>IsSelfMade (Binary indicator)</li>
    </ul>
    <p><strong>Models Built:</strong></p>
    <ul>
      <li>Linear Regression</li>
      <li>Random Forest Regressor</li>
    </ul>
    <p>Both models were trained and evaluated using metrics such as R², RMSE, and MAE.</p>
  </li>

  <li><strong>Results Summary</strong>
    <p><strong>Model &nbsp;&nbsp; R² Score &nbsp;&nbsp; RMSE &nbsp;&nbsp; MAE</strong></p>
    <p>Linear Regression &nbsp;&nbsp; 0.93 &nbsp;&nbsp; 0.40 &nbsp;&nbsp; 0.34</p>
    <p>Random Forest &nbsp;&nbsp; 0.78 &nbsp;&nbsp; 0.70 &nbsp;&nbsp; 0.49</p>
    <p><strong>Interpretation:</strong></p>
    <ul>
      <li>Linear Regression achieved a higher R² score (0.93), indicating better predictive performance on this small dataset.</li>
      <li>Random Forest showed more flexibility but performed less effectively due to limited data size.</li>
    </ul>
  </li>

  <li><strong>Insights &amp; Discussion</strong>
    <ul>
      <li>Top Country: United States</li>
      <li>Top Industry: Technology</li>
      <li>Most Common Wealth Source: Self-Made</li>
      <li>Average Age: Around 60 years</li>
    </ul>
    <p><strong>Limitations:</strong></p>
    <ul>
      <li>Small dataset (20 records only)</li>
      <li>Missing economic indicators like revenue, assets, or company valuation</li>
    </ul>
    <p><strong>Future Work:</strong></p>
    <ul>
      <li>Use larger datasets from reliable financial sources (e.g., Forbes, Bloomberg)</li>
      <li>Apply advanced algorithms (XGBoost, SVR, Neural Networks)</li>
      <li>Include time-series analysis for billionaire wealth trends</li>
    </ul>
  </li>

  <li><strong>Tools and Libraries Used</strong>
    <ul>
      <li>Python, Google Colab</li>
      <li>pandas, NumPy — data analysis</li>
      <li>matplotlib, seaborn — visualization</li>
      <li>scikit-learn — machine learning</li>
    </ul>
  </li>

  <li><strong>Team Members</strong>
    <p><strong>&nbsp;&nbsp;&nbsp;Name &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ID</strong></p>
    <ul>
      <li>Gedamu Ayana &nbsp;&nbsp;  1238</li>
      <li>Hayimanot Kinde &nbsp;0070</li>
      <li>Abye Alemayehu &nbsp;0373</li>
      <li>Firehwot Abeje &nbsp;&nbsp; 0345</li>
      <li>Biniyam Kebere &nbsp;&nbsp; 0240</li>
    </ul>
  </li>

  <li><strong>Repository Structure</strong>
    <pre>
Data-Mining-Project-Billionaires/
 ┣ mining1.ipynb
 ┣ README.md
 ┗ datasets/
     ┗ billionaires_2024.csv
    </pre>
  </li>
</ol>

</div>
