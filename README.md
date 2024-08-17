<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Data Dashboard</title>
</head>
<body>
    <h1>Simple Data Dashboard</h1>
    <p>This is a simple and interactive data dashboard built using Streamlit, a Python framework for building web applications. The dashboard allows users to upload a CSV file, filter data, and visualize it with a line chart. The interface is designed to be intuitive and user-friendly.</p>

    <h2>Features</h2>
    <ul>
        <li><strong>File Upload:</strong> Upload your CSV files for analysis.</li>
        <li><strong>Data Preview:</strong> View the first few rows of your dataset.</li>
        <li><strong>Data Summary:</strong> Get statistical summaries of your data.</li>
        <li><strong>Data Filtering:</strong> Filter data based on specific column values.</li>
        <li><strong>Data Visualization:</strong> Generate a line chart to visualize the data.</li>
    </ul>

    <h2>How to Use</h2>
    <ol>
        <li><strong>Upload a CSV File:</strong> Click the "Choose a CSV file" button and select a file from your computer.</li>
        <li><strong>Preview Data:</strong> Once the file is uploaded, the first few rows of the dataset will be displayed.</li>
        <li><strong>View Summary:</strong> A summary of the data, including statistical metrics, will be shown.</li>
        <li><strong>Filter Data:</strong> Select a column and a specific value to filter the data.</li>
        <li><strong>Generate Plot:</strong> Choose columns for the x and y axes, and generate a line chart.</li>
    </ol>

    <h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li>Streamlit</li>
        <li>Pandas</li>
        <li>Matplotlib</li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/your-repo/simple-data-dashboard.git
cd simple-data-dashboard</code></pre>
        <li>Install the required libraries:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Run the application:</li>
        <pre><code>streamlit run app.py</code></pre>
    </ol>

    <h2>Sample Screenshot</h2>
    <p><img src="screenshot.png" alt="Simple Data Dashboard"></p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>
