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


<em>git clone https://github.com/swagger-api/swagger-editor.git</em><br>
<em>cd swagger-editor</em><br>
<em>npm start</em><br>


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

<h3>Dec 3rd - Updates</h3>

Added theme requests and credit card requests<br>

<h3>Feb 10th - Updates</h3>

Added 9 new requests(post)<br>
<em>POST /uevent/deleteEvent</em><br>
<em>POST /uevent/findEventById</em><br>
<em>POST /uevent/findEventsCompany</em><br>
<em>POST /uevent/updateEvent</em><br>
<em>POST /uevent/addEvent</em><br>
<em>POST /uevent/addEventVisitor</em><br>
<em>POST /uevent/findEventVisitorByEmail</em><br>
<em>POST /uevent/updateEventVisitor</em><br>
<em>POST /uevent/findAllEventVisitors</em><br>

<h3>Mar 16th - Updates</h3>

Added 6 new requests(post)<br>
<em>POST /uship/getAvailableServices</em><br>
<em>POST /uship/deleteCPShipments</em><br>
<em>POST /uship/findCPShipmentInfoByGroupDate</em><br>
<em>POST /uship/getPlatformId</em><br>
<em>POST /uship/getCompanyServiceProviderByName</em><br>
<em>POST /uship/findCPShipmentsByGroupPeriod</em><br>

Deleted 6 requests(post)<br>
<em>POST /uship/shipmentLabel</em><br>
<em>POST /uship/canadaPostServices</em><br>
<em>POST /uship/canadaPostRates</em><br>
<em>POST /uship/shipmentComplete</em><br>
<em>POST /uship/shipmentManifest</em><br>
<em>POST /uship/canadaPostAllowedServices</em><br>

<h3>May 26th - Updates</h3>

Added 6 new requests(post)<br>
<em>POST /uship/transmitCPShipments</em><br>
<em>POST /uship/findCPGroupManifestIds</em><br>
<em>POST /uship/findCPGroupPeriod</em><br>
<em>POST /uship/getCPShipments</em><br>
<em>POST /uship/voidCPShipments</em><br>
<em>POST /uship/getCPManifestIds</em><br>
<em>POST /uship/getCPMissingManifests</em><br>
<em>POST /uship/getCPGroups</em><br>
<em>POST /uship/getCPManifestAgain</em><br>
