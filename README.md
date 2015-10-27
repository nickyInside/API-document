# API-document
====================

author: [Naoki Tanaka](naoki.tanaka@machool.com)

version: 1.1.0

This is API documentation for uShipApp. I created with Swagger editor (http://swagger.io/). 

It displays all APIs which include uMan, uShip, uAnalyze, and uLog.
You can add, delete, and modify those APIs by Swagger editor.


<strong>To use Swagger editor locally:</strong>
(Make sure you have node.js installed)


1. open terminal
 

2. type these codes


<em>git clone https://github.com/swagger-api/swagger-editor.git</em>
<em>cd swagger-editor</em>
<em>npm start</em>


It build automatically and opens browser window.

<h3>Aug 4th - Updates</h3>

Added APIs for Machool service plans, billing information

uDo API documentation is now on server so you can access the document without setting up locally!

URL: http://uservice.machool.com:3000/ *The port is not activated now(Oct, 27th 2015)

If the browser does not display our API documentation, download JSON or yaml file from our repository and import either one of them. 


<h3>Oct 1st - Updates</h3>

Added uPay and uVisit APIs, modified some objects, and edited description.  

<h3>Oct 20th - Updates</h3>

Added uContent(request documents, filter documents, and zip documents)

<h3>Oct 27th - Updates</h3>

Added 2 post requests, and modified 1 request<br>
<em>POST /uman/updateCompanyInfo</em> - Added Company Logo, and changed address<br>
<em>POST /uman/updateCompanyAddress</em> - Added new request<br>
<em>POST /uman/saveContactInfo</em> - Added new request<br>
