https://gallery-shop-tnadezda.herokuapp.com/


Specification 

Using MongoDB Collection

Gallery Collection
FILENAME	DESCRIPTION	PRICE	STATUS
abcd.jpg	Whatever that is appropriate	2000	A
efgh.jpg	Whatever that is appropriate	2500	A
ijkl.jpg	Whatever that is appropriate	3200	A
mnop.jpg	Whatever that is appropriate	6700	A

Creating New Order and Purchase Webpage

•	The order and purchase functionality are to be coded in a separate JavaScript file using Express.Router and imported by the web server program
•	Elements that identifies the selected image and the price 
•	The name and description of the displayed image and its price are to be retrieved from the new Gallery collection
•	Two buttons: one button with the caption BUY and the other with the caption CANCEL
•	When clicking the BUY button, a message box showing SOLD is to be displayed
•	When clicking the CANCEL button, a message box showing MAYBE NEXT TIME is to be displayed
•	After clicking the OK button on either message box, the control is to return to the Gallery webpage
•	When returning to the Gallery webpage after cancelling the purchase, the image that was to be purchased is to be displayed on the Gallery page.
•	When returning to the Gallery webpage after purchasing the image, the default image is to be displayed on the Gallery page.
•	When one buys an image from the Gallery by clicking the BUY button, the status of that image on the database must be changed from “A” (Available) to “S” (Sold)
•	The remaining design criteria are to be decided by the web page designer

Modifying Existing Gallery Webpage

•	Only the images that are unsold (available) can be displayed for selection
•	The image selection is to be presented via a dropdown list
•	Click on a shown image, excluding the default image, invokes the download and display of the new Order and Purchase webpage
•	All image-related data are now in the new MongoDB collection and no longer retrieved from your imagelist.txt file: you are to modify this webpage to utilize the new collection
•	All other functionalities on this page should remain unaffected
Modify Existing Login Web Page

•	When one first log on to your webpage, be sure to have the status values of all documents initialized to “A” (available)
•	All other functionalities on this page should remain unaffected

Technical Specification

•	Code one JavaScript server application using Node.js for routing, Express.js for framework and Handlebars.js (including usage of partials) for templating 
•	npm modules are: express, express-handlebars, mongoose, path, body-parser, fs and client-sessions

