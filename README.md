# WELCOME TO MY LANDING PAGE
<html>
<body>

<h2>Please submit the form to save your information in my database</h2>
<div class="container-fluid">
	<div class="row">
		<div class="col-md-12">
<form action="/action_page.php">
  First name:<br>
  <input type="text" name="firstname"><br>
  Last name:<br>
  <input type="text" name="lastname"><br>
  Favorite color:<br>
  <input type="radio" name="gender" value="Rojo" checked>Rojo<br>
  <input type="radio" name="gender" value="Azul"> Azul<br>
  <input type="radio" name="gender" value="Amarillo"> Amarillo<br>
  <input type="submit" value="Submit"> 
</form>
		</div>
	</div>
</div>
</body>
</html>

{
    "name": "DemoForm",
    "action": "",
    "method": "",
    "cssClass": "",
    "redirect": "",
    "submitText": "Submit",
    "followUpId": "",
    "notifyRecipients": "",
    "leadNurturingCampaignId": "",
    "formFieldGroups": [
        {
            "fields": [
                {
                    "name": "firstname",
                    "label": "First Name",
                    "type": "string",
                    "fieldType": "text",
                    "description": "",
                    "groupName": "",
                    "displayOrder": 0,
                    "required": false,
                    "selectedOptions": [],
                    "options": [],
                    "validation": {
                        "name": "",
                        "message": "",
                        "data": "",
                        "useDefaultBlockList": false
                    },
                    "enabled": true,
                    "hidden": false,
                    "defaultValue": "",
                    "isSmartField": false,
                    "unselectedLabel": "",
                    "placeholder": ""
                }
            ],
            "default": true,
            "isSmartGroup": false
        },
        {
            "fields": [
                {
                    "name": "lastname",
                    "label": "Last Name",
                    "type": "string",
                    "fieldType": "text",
                    "description": "",
                    "groupName": "",
                    "displayOrder": 1,
                    "required": false,
                    "selectedOptions": [],
                    "options": [],
                    "validation": {
                        "name": "",
                        "message": "",
                        "data": "",
                        "useDefaultBlockList": false
                    },
                    "enabled": true,
                    "hidden": false,
                    "defaultValue": "",
                    "isSmartField": false,
                    "unselectedLabel": "",
                    "placeholder": ""
                }
            ],
            "default": true,
            "isSmartGroup": false
        },
        {
            "fields": [
                {
                    "name": "adress_1",
                    "label": "Adress 1",
                    "type": "string",
                    "fieldType": "text",
                    "description": "",
                    "groupName": "",
                    "displayOrder": 2,
                    "required": false,
                    "selectedOptions": [],
                    "options": [],
                    "validation": {
                        "name": "",
                        "message": "",
                        "data": "",
                        "useDefaultBlockList": false
                    },
                    "enabled": true,
                    "hidden": false,
                    "defaultValue": "",
                    "isSmartField": false,
                    "unselectedLabel": "",
                    "placeholder": ""
                }
            ],
            "default": true,
            "isSmartGroup": false
        }
    ],
    "createdAt": 1318534279910,
    "updatedAt": 1413919291011,
    "performableHtml": "",
    "migratedFrom": "ld",
    "ignoreCurrentValues": false,
    "metaData": [],
    "deletable": true
}

The response from this API call are standard 
REST-style HTTP response codes that mark success 
or failure, along with the JSON representing the 
form that you just created. See below for a 
sample of this JSON output.

200 when a new form is created
401 when an unauthorized request is made
500 when an internal server error occurs
Example response body on success (200 response):

  {
    "portalId": 62515,
    "guid": "c4c42070-c856-4a49-95cf-a02d32d05286",
    "name": "Docs creation test",
    "action": "",
    "method": "",
    "cssClass": "",
    "redirect": "",
    "submitText": "Submit",
    "followUpId": "",
    "notifyRecipients": "",
    "leadNurturingCampaignId": "",
    "formFieldGroups": [
        {
            "fields": [
                {
                    "name": "firstname",
                    "label": "First Name",
                    "type": "string",
                    "fieldType": "text",
                    "description": "",
                    "groupName": "",
                    "displayOrder": 0,
                    "required": false,
                    "selectedOptions": [],
                    "options": [],
                    "validation": {
                        "name": "",
                        "message": "",
                        "data": "",
                        "useDefaultBlockList": false
                    },
                    "enabled": true,
                    "hidden": false,
                    "defaultValue": "",
                    "isSmartField": false,
                    "unselectedLabel": "",
                    "placeholder": ""
                }
            ],
            "default": true,
            "isSmartGroup": false
        },
        {
            "fields": [
                {
                    "name": "lastname",
                    "label": "Last Name",
                    "type": "string",
                    "fieldType": "text",
                    "description": "",
                    "groupName": "",
                    "displayOrder": 1,
                    "required": false,
                    "selectedOptions": [],
                    "options": [],
                    "validation": {
                        "name": "",
                        "message": "",
                        "data": "",
                        "useDefaultBlockList": false
                    },
                    "enabled": true,
                    "hidden": false,
                    "defaultValue": "",
                    "isSmartField": false,
                    "unselectedLabel": "",
                    "placeholder": ""
                }
            ],
            "default": true,
            "isSmartGroup": false
        },
        {
            "fields": [
                {
                    "name": "adress_1",
                    "label": "Adress 1",
                    "type": "string",
                    "fieldType": "text",
                    "description": "",
                    "groupName": "",
                    "displayOrder": 2,
                    "required": false,
                    "selectedOptions": [],
                    "options": [],
                    "validation": {
                        "name": "",
                        "message": "",
                        "data": "",
                        "useDefaultBlockList": false
                    },
                    "enabled": true,
                    "hidden": false,
                    "defaultValue": "",
                    "isSmartField": false,
                    "unselectedLabel": "",
                    "placeholder": ""
                }
            ],
            "default": true,
            "isSmartGroup": false
        }
    ],
    "createdAt": 1431474404764,
    "updatedAt": 1431474404764,
    "performableHtml": "",
    "migratedFrom": "ld",
    "ignoreCurrentValues": false,
    "metaData": [],
    "deletable": true
}
