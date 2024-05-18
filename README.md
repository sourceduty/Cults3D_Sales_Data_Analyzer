![Cults3D Sales Data Tool](https://github.com/sourceduty/Cults3D_Sales_Data_Analyzer/assets/123030236/7001e307-8329-4d81-b303-b0990d3b4f3e)

> Open Cults3D CSV sale data files, view the processed data, and export a detailed statistical report.

#

The Cults3D Sales Data Analyzer is a Python application with a graphical user interface (GUI) built using the tkinter library. This application allows users to open CSV files, view the processed data, and export a detailed statistical report. The core functionality revolves around data cleaning, analysis, and report generation, which are facilitated by the pandas library for data manipulation.

When the application is launched, it presents a simple GUI with buttons for opening CSV files and exporting reports, and a text area for displaying the analysis results. The user starts by clicking the "Open CSV" button, which triggers a file dialog to select a CSV file containing sales data. The selected file is then read into a pandas DataFrame, and any rows with all NaN values are removed. The application also fills missing values with appropriate defaults: zeros for numerical columns and empty strings for text columns. Additionally, it ensures that data types are correctly assigned to each column, such as converting date strings to datetime objects and numeric columns to appropriate numerical types.

Once the data is cleaned, it is analyzed to generate summary statistics and sort the data. The summary statistics include counts, means, minimums, and maximums for key numerical columns like total sales before tax, VAT, commission, and income. The data is sorted by date and total sales to identify the top transactions. Furthermore, the data is grouped by user and buyer country to aggregate total sales and other financial metrics, providing insights into the performance across different users and regions.

The results of the analysis are displayed in the text area of the GUI, formatted as a comprehensive report. This report includes summary statistics, details of the top transaction, and aggregated data grouped by user and buyer country. If the user wishes to save this report, they can click the "Export Report" button, which opens a save dialog to specify the file location and name. The report is then written to a text file, ensuring that the user can retain and share the analysis results.

Overall, the Cults3D Sales Data Analyzer provides a user-friendly interface for performing detailed analysis of sales data, making it accessible to users who may not be familiar with programming or data manipulation tools. By combining the capabilities of tkinter for the GUI and pandas for data processing, the application offers a robust solution for handling and interpreting sales data.

#
### Example Report

[Example Report.txt](https://github.com/sourceduty/Cults3D_Sales_Data_Analyzer/files/15366813/Example.Report.txt)

***
🛈 This software is free and open-source; anyone can redistribute it and/or modify it.
