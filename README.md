<H1 ALIGN=CENTER> SENTIMENTAL ANALYSIS ON ANY DATASET USING RAPID MINER </H1>
<H3> NAME : SHRRUTHILAYA G </H3>
<H3> REGISTER NUMBER : 212221230097 </H3>
<H3>EXPERIMENT NO : 10 </H3>
<H3>DATE  : 27.04.2024 </H3>

## AIM: 
To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
## DESCRIPTION: 
Sentiment analysis is the process of using computational techniques to determine the sentiment expressed in text data, such as positive, negative, or neutral. It helps businesses understand customer opinions and make data-driven decisions based on public sentiment.

## PROCEDURE:
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

## OUTPUT:
![image](https://github.com/pavizhi/WDM_EXP10/assets/95067176/563e2378-9c07-4478-aab2-f9ba8bb61917)
![image](https://github.com/pavizhi/WDM_EXP10/assets/95067176/70b5c021-0de6-4dbe-8503-d545e5072c57)
![image](https://github.com/pavizhi/WDM_EXP10/assets/95067176/1344c1a2-e0c1-442f-871a-6a63cba73ee2)


## RESULT:
Thus, sentimental analysis for twitter data using Rapidminer is done successfully.
