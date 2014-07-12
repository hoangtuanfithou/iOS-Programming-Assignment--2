iOS-Programming-Assignment--2
=============================

iOS Programming Assignment #2
[DO NOT USE COREDATA FOR THIS]

Requirements

Use the latest Xcode and the project is created through File >New.
ARC enabled. 
Must support iOS 6 or higher.
Must support iPhone 4S and iPhone 5 screen sizes.
Use Image Assets container for images.


Assignment.

Review the Macy’s Objective C Style Guide.

https://github.com/johnnst/objective-c-style-guide

Review the following model.

Class = Product
Fields
id
name
description
regular price
sale price
product photo (image)
colors (array)
stores (dictionary)

Create a new app that showcases the following.
Creation of the model.
Create mock data for the models using json. Show case at least 3 mock products.
Use of sqlite to store the model. Implement the following.
INSERT
SELECT
DELETE
UPDATE
Provide the main view controller will have a button that is labeled “Show Product” and “Create Product”.
Start with “Create Product” from the json data. You can either create buttons that say “Create Product 1”, “Create Product 2”, etc, OR show a better way to dynamically create these products.  This should effective INSERT a row into the products table.
Next, “Show Product” should provide the user with a list of products in the database and selecting a product brings you to a product page. (Hint: Use SELECT statements)
Create a new view controller that shows the product. You have freedom of UX here on how you want the information to be displayed.
Provide buttons to “Update” and “Delete”. 
Touching the image thumbnail will show a full size image.
Please deliver view controllers and cells as h, m, and nib files. The only exception is the first view controller launched from the storyboard.
Please use as much as possible, UI objects from the native framework. 
Feel free to use any images or crop what’s available in the existing app. 
Please code to the Macy’s Objective C Style Guide. Also provide a summary of your approach and design decisions.
Document any 3rd party libraries used and why.
Unit tests is optional but a big plus (XCTest framework only).


After you are done, submit via github or bitbucket.
