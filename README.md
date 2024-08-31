### EX:10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 31-08-24 
### AIM: 
To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">
Sentiment analysis, also known as opinion mining, is the process of using natural language processing (NLP), text analysis, and computational linguistics to identify and extract subjective information from text data. The goal of sentiment analysis is to determine the emotional tone behind a body of text, which can be positive, negative, or neutral.
    
### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
![image](https://github.com/user-attachments/assets/0c15a489-b524-42ee-afbd-b687a7f8309b)
![image](https://github.com/user-attachments/assets/4e4f315a-947a-4081-a77e-8a06869b8b4d)

### Result:
Thus, Sentimental Analysis on Any Dataset a Using Rapidminer has been executed successfully.
