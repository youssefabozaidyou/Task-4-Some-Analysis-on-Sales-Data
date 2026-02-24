<!DOCTYPE html>

<html lang="en">

<head>

&nbsp;   <meta charset="UTF-8">

&nbsp;   <title>Sales Data Analysis - Task Documentation</title>

</head>

<body style="font-family: Arial, sans-serif; line-height: 1.7; padding: 20px; color: #333;">



&nbsp;   <h1>📊 Sales Data Analysis - Task</h1>



&nbsp;   <p>

&nbsp;       This project is a comprehensive <strong>Sales Data Analysis \\\& Visualization Task</strong>. 

&nbsp;       The focus was on cleaning a sales dataset, performing statistical analysis, and generating 

&nbsp;       business-oriented visual insights using Python. This task demonstrates proficiency in 

&nbsp;       data manipulation with <code>Pandas</code> and interactive visualization with <code>Plotly Express</code>.

&nbsp;   </p>



&nbsp;   <hr>



&nbsp;   <h2>📝 Task Objectives</h2>

&nbsp;   <p>The primary objectives of this analysis were to:</p>

&nbsp;   <ul>

&nbsp;       <li>Ensure data integrity through <strong>Data Cleaning</strong> (Handling dates and nulls).</li>

&nbsp;       <li>Calculate essential business <strong>KPIs</strong> (Total Sales, Average Order Value).</li>

&nbsp;       <li>Analyze <strong>Temporal Trends</strong> to identify sales growth and seasonal patterns.</li>

&nbsp;       <li>Perform <strong>Comparative Analysis</strong> across Products, Managers, Cities, and Payment Methods.</li>

&nbsp;   </ul>



&nbsp;   <hr>



&nbsp;   <h2>📂 Project Structure</h2>

&nbsp;   <p>The project is organized for clarity and easy navigation:</p>

&nbsp;   <ul>

&nbsp;       <li><strong>Dataset</strong>: <code>9. Sales-Data-Analysis.csv.xlsx</code> (The source data).</li>

&nbsp;       <li><strong>Notebook</strong>: The Jupyter Notebook containing the Python code and <code>Plotly</code> visualizations.</li>

&nbsp;       <li><strong>README.html</strong>: This documentation file.</li>

&nbsp;   </ul>



&nbsp;   <hr>



&nbsp;   <h2>🛠️ Analysis Steps (What I did)</h2>



&nbsp;   <h3>1. <strong>Data Loading \\\& Cleaning</strong></h3>

&nbsp;   <ul>

&nbsp;       <li>Loaded the dataset and standardized column names using <code>.str.strip()</code> to remove extra spaces.</li>

&nbsp;       <li>Created a custom function <code>func(df)</code> to:

&nbsp;           <ul>

&nbsp;               <li>Convert the <strong>Date</strong> column to a proper <code>datetime</code> format.</li>

&nbsp;               <li>Fill any missing values using the column mean (<code>fillna</code>).</li>

&nbsp;               <li>Convert types to <strong>Category</strong> or <strong>String</strong> for optimization.</li>

&nbsp;           </ul>

&nbsp;       </li>

&nbsp;   </ul>



&nbsp;   <h3>2. <strong>Overall Sales Metrics</strong></h3>

&nbsp;   <p>Calculated the core financial figures:</p>

&nbsp;   <ul>

&nbsp;       <li><strong>Total Sales</strong>: Derived from <code>Price per unit \* Quantity</code>.</li>

&nbsp;       <li><strong>Mean \\\& Median</strong>: To understand the central tendency of sales.</li>

&nbsp;       <li><strong>Max \\\& Min</strong>: To identify the highest and lowest transaction values.</li>

&nbsp;   </ul>



&nbsp;   <h3>3. <strong>Time-Based Analysis</strong></h3>

&nbsp;   <ul>

&nbsp;       <li>Extracted <strong>Day</strong> and <strong>Month</strong> from the date column.</li>

&nbsp;       <li>Identified the <strong>Top Month</strong> (November) and <strong>Low Month</strong> (May).</li>

&nbsp;       <li>Created a <strong>Trend Line</strong> visualization showing a steady/seasonal increase in sales.</li>

&nbsp;   </ul>



&nbsp;   <h3>4. <strong>Business Visualizations</strong></h3>

&nbsp;   <p>Generated several interactive plots using <code>Plotly Express</code>:</p>

&nbsp;   <ul>

&nbsp;       <li><strong>Product Performance</strong>: Bar charts showing total sales and average price per product (Colors: <strong>Red</strong>, <strong>Purple</strong>).</li>

&nbsp;       <li><strong>Manager Ranking</strong>: A ranked bar chart of manager performance (Color: <strong>Red</strong>).</li>

&nbsp;       <li><strong>Geographic Insights</strong>: A pie chart displaying the revenue contribution of each <strong>City</strong>.</li>

&nbsp;       <li><strong>Payment \\\& Purchase Channels</strong>: Analyzed <strong>Payment Methods</strong> (Color: <strong>Turquoise</strong>) and compared <strong>Online vs. In-store</strong> sales.</li>

&nbsp;   </ul>



&nbsp;   <hr>



&nbsp;   <h2>🚀 Technologies Used</h2>

&nbsp;   <ul>

&nbsp;       <li><strong>Python 3.x</strong></li>

&nbsp;       <li><strong>Pandas</strong>: For data cleaning and aggregation.</li>

&nbsp;       <li><strong>Plotly Express</strong>: For creating interactive and aesthetic visualizations.</li>

&nbsp;       <li><strong>NumPy</strong>: For numerical calculations.</li>

&nbsp;   </ul>



&nbsp;   <hr>



&nbsp;   <h2>⚙️ How to Run</h2>

&nbsp;   <ol>

&nbsp;       <li>Ensure you have the Excel file in the correct directory.</li>

&nbsp;       <li>Install the required Python libraries:

&nbsp;           <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px;"><code>pip install pandas plotly openpyxl</code></pre>

&nbsp;       </li>

&nbsp;       <li>Run the code cells to generate the interactive charts.</li>

&nbsp;   </ol>



</body>

</html>

