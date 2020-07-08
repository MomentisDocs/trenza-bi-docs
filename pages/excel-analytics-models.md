<!-- markdownlint-disable MD033 -->

# Using Excel to Connect to Analytics Models

If you do not already have an existing Excel spreadsheet connected to the analytics models, open a Power BI dashboard and click "Analyze in Excel",

<img src="../assets/img/excel-analytics-models-analyze-in-excel.png" width="500" height="348" />

If the following message appears, it is simply informing you that for security reasons, you will need to sign in from within Excel when connecting to the analytics models. Click "Open in Excel".

<img src="../assets/img/excel-analytics-models-open-in-excel.png" width="600" height="308" />

You might also be presented with this message to make sure that you have the latest Excel updates to be able to connect to analytics models. You can click on "Learn more about this update" for details but in summary, if you have Microsoft Excel 2010 SP1 and later, you shouldn't have to update or install anything else.

<img src="../assets/img/excel-analytics-models-excel-updates.png" width="600" height="374" />

Click "I've already installed these updates",

<img src="../assets/img/excel-analytics-models-excel-updates-already-installed.png" width="600" height="420" />

Your browser will download an "odc" file.

<img src="../assets/img/excel-analytics-models-odc-download.png" width="300" height="179" />

The ODC file extension is an Office Data Connection File which was developed by Microsoft. The file format is a connection information file that contains properties to connect to and retrieve data from an external data source.

Open Excel, create a new blank workbook, click "Data", and click "Existing Connections",

<img src="../assets/img/excel-analytics-models-excel-existing-connections.png" width="600" height="547" />

"Browse for More..." and then select the "odc" file.

<img src="../assets/img/excel-analytics-models-excel-existing-connections-browse.png" width="400" height="405" />

<img src="../assets/img/excel-analytics-models-excel-existing-connections-browse-file.png" width="500" height="434" />

For security reasons, you will need to log in with your Office 365 account. Only authenticated users with assigned security access will be able to connect to the corporate data.

Sign in with your Office 365 credentials.

<img src="../assets/img/excel-analytics-models-excel-sign-in.png" width="500" height="619" />

These are [measures](https://docs.microsoft.com/en-us/analysis-services/tabular-models/measures-ssas-tabular):

<img src="../assets/img/excel-analytics-models-excel-pivot-table-measures.png" width="400" height="351" />

These are [dimensions](https://docs.microsoft.com/en-us/analysis-services/multidimensional-models-olap-logical-dimension-objects/dimensions-introduction):

<img src="../assets/img/excel-analytics-models-excel-pivot-table-dimensions.png" width="400" height="359" />

<img src="../assets/img/excel-analytics-models-excel-pivot-table.png" width="800" height="481" />

You can save the spreadsheet. When you reopen it at a later date, you will need click "Enable Content". 

<img src="../assets/img/excel-analytics-models-excel-enable-content.png" width="500" height="94" />