# Jira
Setting up of Jira profile, configs etc:-

### Basic requirements
* Email-id

### Resources
    - https://aserve.atlassian.net/wiki/spaces/PBCFJC/pages/2346352641/How+to+connect+to+Microsoft+Power+BI+using+Jira+API+Token
    - https://marketplace.atlassian.com/apps/1221150/power-bi-connector-for-jira?tab=overview&hosting=cloud
    
### Setup
  - Go to the marketplace link and click the 'free try button' in the powerbi connector for jira page; this will initiate/install the connector
  - Next login to your Jira page using your Jira login
  - Click your profile button on the top-right corner
  - Go to 'Security' session
  - Click create API token (Refer to the first reference doc in the above resources page)
  - Give the requisite connector name
  - Copy the API token using the copy button
  - Click the 'powerbi connector for Jira' button in the Apps section in the top (sometimes the apps section could be hidden under the more button in the top)
  - Go to connectors page (on the left) and click create a data source
  - Select all requisite data field and click Save; this will create the requisite data source
  - Go to token page by clicking the connectors session on the left
  - Enter your Jira email and the copied API token; Click validate and Save
  - Go to the connectors page on the left and copy the requisite URL
  
### Integration with PowerBI
  - Open PowerBi desktop
  - In get data session, click OData Feed and enter the copied URL
  - The first attempt would be a failure and would connect you to a more advanced page
  - In this, add the login Jira email as the username and the API token as the password
  - Click connect and the choose/transform the requisite data fields so as to kickstart the exploratory visualization stage of the Jira data
  
