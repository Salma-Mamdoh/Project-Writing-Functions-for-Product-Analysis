<!DOCTYPE html>
<html>
<head>
   <h1>DRY: NPS Analysis Project ✨✨</h1>
</head>
<body>
    <h1>Introduction</h1>
    <p>This project showcases the implementation of the "Don't Repeat Yourself" (DRY) programming principle in the context of Net Promoter Score (NPS) analysis. It revolves around optimizing repetitive code, enhancing data consolidation, and improving the overall efficiency of NPS data analysis.</p>
    
   <h2>Key Steps:</h2>
    <ol>
        <li><strong>Reading and Converting CSVs:</strong> A function is introduced to read and convert NPS data from CSV files. This function streamlines the process by adding the source type and enhances code readability.</li>
        <li><strong>Verifying CSV Validity:</strong> A context manager-based function is implemented to verify the validity of CSV files, reducing the risk of errors during processing.</li>
        <li><strong>Combining DataFrames:</strong> A function is designed to consolidate NPS data from different sources into a single DataFrame. This function minimizes repetition and promotes scalability.</li>
        <li><strong>Categorizing NPS Ratings:</strong> A function categorizes NPS ratings into "Detractor," "Passive," or "Promoter" groups, enhancing data organization.</li>
        <li><strong>Calculating NPS:</strong> The NPS score is calculated using a function that encapsulates the calculation logic, making it reusable and reducing redundancy.</li>
        <li><strong>Breaking Down NPS by Source:</strong> The analysis is extended to break down NPS scores by source, providing valuable insights.</li>
        <li><strong>Adding Docstrings:</strong> Comprehensive docstrings are added to all functions, enhancing code readability and reusability.</li>
    </ol>
    
  <p>This project demonstrates how applying the DRY principle through functions, context managers, and proper documentation can streamline NPS analysis workflows and facilitate collaboration.</p>
</body>
</html>
