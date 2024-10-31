![Cults3D Sales Data Tool](https://github.com/sourceduty/Cults3D_Sales_Data_Analyzer/assets/123030236/6a91ca57-5df5-48cd-bd15-b1b3d00caeb7)

> Open Cults3D CSV sale data files, view the processed data, and export a detailed statistical report.

#

Cults3D Sales Data Analyzer V1.5 program is a comprehensive Python application with a graphical user interface (GUI) built using the tkinter library. This application enables users to load multiple CSV files from a specified folder, process the combined data, and generate a detailed statistical report. The key functionalities of this program include data cleaning, analysis, and report generation, all facilitated by the pandas library for data manipulation.

When the application is launched, it presents a GUI with buttons for opening a folder, viewing the data, and exporting the report. The user starts by clicking the "Open Folder" button, which triggers a folder selection dialog. Upon selecting a folder, the program scans the folder for CSV files and loads each file into a pandas DataFrame. These individual DataFrames are then concatenated into a single DataFrame, combining the data from all CSV files. This combined dataset undergoes cleaning to handle missing values, ensuring numerical columns are filled with zeros and text columns with empty strings. Additionally, data types are corrected, with date strings converted to datetime objects and numerical columns to appropriate numerical types.

Once the data is cleaned, the program performs a comprehensive analysis. It generates summary statistics, such as counts, means, minimums, and maximums for key numerical columns like total sales before tax, VAT, commission, and income. Additional metrics are calculated, including total sales, average sales per transaction, and the top-selling design. The data is also sorted by date and total sales to highlight significant transactions. Furthermore, the data is grouped by user and buyer country to aggregate total sales and other financial metrics, providing insights into performance across different users and regions.

The results of this analysis are displayed in the text area of the GUI, formatted as a comprehensive report. This report includes summary statistics, additional metrics, details of the top transaction, and aggregated data grouped by user and buyer country. If the user wishes to save this report, they can click the "Export Report" button, which opens a save dialog to specify the file location and name. The report is then written to a text file, ensuring that the user can retain and share the analysis results.

Overall, the Cults3D Sales Data Analyzer V1.5 provides a user-friendly interface for performing detailed analysis of sales data from multiple CSV files, making it accessible to users who may not be familiar with programming or data manipulation tools. By combining the capabilities of tkinter for the GUI and pandas for data processing, the application offers a robust solution for handling and interpreting large volumes of sales data, delivering valuable insights and facilitating informed decision-making.

#
![3D](https://github.com/user-attachments/assets/126cdb47-40c3-4703-adfe-19b4a524a513)

#
### Example Report

[Example Report.txt](https://github.com/sourceduty/Cults3D_Sales_Data_Analyzer/files/15366813/Example.Report.txt)

***
🛈 This software is free and open-source; anyone can redistribute it and/or modify it.
