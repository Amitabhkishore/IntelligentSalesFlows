ReadMe 
​
## Overview
​
Intelligent Sales Sample Flows for Field Inventory Management with Health Cloud allows to manage inventories and cycle counts, and ultimately increase medical device sales. 

## Business Objective
​
The business objective of the Intelligent Sales Sample Flows for Field Inventory Management is to fulfil the med device needs of the providers by effectively capturing the device request, handing over the device, and retrieving the device. Along with that, the sample flows also aim to track missing inventory during cycle counting by marking them against right orders or as lost. 
​
## Business Value and Benefits
​
- Faster device request capture and handover
- Increased provider satisfaction
- Improved patient care
- Increased product revenue
- Reduction in product write offs
- Approval compliant product delivery
​​​
### Industry:
​
- Healthcare- Lifesciences
​
### User Persona:
​
- Sales Representatives

### User Workflow:
​
- Sample Request Management (Request Capture and Request Fulfillment)      
- Trial Request Management (Request Capture and Request Fulfillment)
- Loan Request Management (Request Capture and Request Fulfillment)  
- Product Retrieval Management (Retrieval of Trial and Loan Products)  
- Mark as Lost
- Relate to Order 
------
​
## Package Includes:

Following are included in the package: 

- Aura
- classes
- flexipages
- flows
- labels
- lwc
- objects
- package.xml
- profiles
- ReadMe
- standardValueSets
- tabs

​
## Configuration Requirements
​
### Pre-Install Configuration Steps:

- Intelligent Sales Data Setup
- Enable the Intelligent Sales and Visit Inventory Management
- Assign the ActionPlans, Health Cloud Foundation, and Industries Visits permission sets
​
#### Install the Flow Package

1. Download the package from GitHub.
2. Unzip the file and compress all the folders along with package.xml.
3. Log into Salesforce on Workbench. 
4. From the dropdown menu that appears under migration, click Deploy.
5. Click Choose file and select your compressed file.
6. Select Check Only, Rollback On Error, and Single Package. 
    1. Selecting Check Only checks if the deployment will be successful before making permanent changes to your org. If the check fails, fix any issues. 
7. Click Next.
8. If the deployment is valid, repeat this process without selecting Check Only to deploy the flows to your org.
​
### Post-Install Configuration Steps:

Configure the Intelligent Sales Flows: 
​
1. From Setup, in the Quick Find box, enter App Manager, and then select App Manager. 
2. Next to Health Cloud - Intelligent Sales, click Dropdown, and then click Edit.
3. In App Settings, click Navigation Items. 
4. In Available Items, move these tabs to the Selected Items column.
    1. Sample Request Management 
    2. Trial Request Management 
    3. Loan Request Management 
    4. Product Retrieval Management
5. Save your work.  
Configure the Intelligent Sales Flows: 

1. From Setup, in the Quick Find box, enter Intelligent Sales Settings, then select Intelligent Sales Settings.
2. In the Configure Actions Button Visibility section, enable Cycle Count Products Page and click Save.
3. Open a Visit record.
4. Click the Gear icon, and then click Edit Page. 
5. In Lightning App Builder, select Phone as the form factor. 
6. Move Visit Overview, Visit Actions, and Task List for Medical Devices components onto the appropriate part of the page.
7. In the Properties pane of Task List for Medical Devices, under Custom Action Flow, select Show More Actions.- From Show More Actions, you can launch Mark as Lost and Relate to Order flows. 
8. Save the settings and activate your changes. 
------
​
## Assumptions
​
1. A customer has licenses for Health Cloud or Health Cloud for Life-sciences. 
2. Intelligent Sales and Visit Inventory Management are enabled. 
3. ActionPlans, Health Cloud Foundation, and Industries Visits permission sets are assigned to the users. 
4. The sample flows are being used in the Mobile Device. 
5. 
​
------
​
## Revision History

- None
