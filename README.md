#Creating a Menu

function mymenu() {
  var ui = SpreadsheetApp.getUi();
  ui.createMenu('My Menu')
      .addItem('Item_name1', 'Function2')
      .addToUi();
}


#Accessing HTML/XML/CSV content via link

function mydata() {
 var csvUrl='https://storage.cloud.google.com/visit-reports-bucket/visit-report-dump/attachments/14-03-2023/Visit_Report_Dump.csv';
  var response = UrlFetchApp.fetch(csvUrl);

}
