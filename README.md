# API-document
====================

author: [Naoki Tanaka](naoki.tanaka@machool.com)

version: 1.1.0

This is API documentation for uShipApp. I created with Swagger editor (http://swagger.io/). 

It displays all APIs which include uMan, uShip, uAnalyze, and uLog.
You can add, delete, and modify those APIs by Swagger editor.


To use Swagger editor locally:
(Make sure you have node.js installed)


1. open terminal
 

2. type these codes


git clone https://github.com/swagger-api/swagger-editor.git
cd swagger-editor
npm start


It build automatically and opens browser window.

Aug 4th - Updates

Added APIs for Machool service plans, billing information

uDo API documentation is now on server so you can access the document without setting up locally!

URL: http://uservice.machool.com:3000/

If the browser does not display our API documentation, download JSON or yaml file from our repository and import either one of them. 


Oct 1st - Updates

Added uPay and uVisit APIs, modified some objects, and edited description.  

Oct 20th - Updates

Added uContent(request documents, filter documents, and zip documents)

Oct 27th - Updates

Added 2 post requests, and modified 1 request
POST /uman/updateCompanyInfo - Added Company Logo, and changed address
POST /uman/updateCompanyAddress - Added new request
POST /uman/saveContactInfo - Added new request
