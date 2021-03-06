#ServiceNow Full Width UI

_**This UI is not endorsed or supported by ServiceNow in any way. Use at your own risk.**_

If you work a lot with big forms and lists in ServiceNow then this might be something for you.

## Features
- Full screen width
- Application menu in alphabetical order 
- No seperators
- No duplicates in history

![Image of Homepage](./images/home.png)

![Image of Application Menu](./images/app-menu.png)

![Image of User Profile Menu](./images/profile-menu.png)

## Installation
### Update Set Method:
1. Navigate to System Update Sets > Retrieved Update Sets
2. Click Import Update Set from XML
3. Upload the file in the update set directory
4. Click on the uploaded record to open the form
5. Click Preview Update Set
6. Click Commit Update Set

### Import XML Method:
**Requires MAINT role**

1. Navigate to any ServiceNow list
2. Right click on the list header and chose Import XML
3. Upload all the files under the records directory

## Usage
Navigate to localhost:8080/better.do

OR

Navigate to YOUR-INSTANCE-NAME.service-now.com/better.do

## Known Limitations
- Not tested
- No RTL support
- No routing via URL parameters
- Does not responsd to ServiceNow themes
- No application picker or update set picker
- Profile avatar doesnt display
- Online status not displayed
- Long menu item names truncated
- Menu items arent refreshed unless entire page is reloaded

## Known Bugs
- Incorrect style applied to close button on impersonate dialog

![Image of Impersonate Dialog](./images/button.png)