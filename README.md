# GTM Template: Salesforce Data Cloud Event Ingestion

The **Salesforce Data Cloud Event Ingestion** template allows automated tracking of engagement and profile events on your website via the Data Cloud website connector. Engagement data you ingest into Data Cloud helps you better understand customer activities and interests.

### Overview
- Sends events to Salesforce Data Cloud for ingestion
- Managed via API without manual configuration
- Configured in Salesforce using a point-and-click interface 

### How It Works
The template is automatically added to the user's Google Tag Manager  (GTM) container when they configure a website connector in Data Cloud. It injects a script tag into the website, dispatching event data to the Data Cloud web connector. Data ingested from your website is ingested into Data Cloud and unified with data about your customers from other sources to enhance your customer profile data. 


### Installation & Setup
1. **API Integration**: The template is programmatically added to your GTM account.
2. **Configuration**: Event types and the Data Cloud Script URL are set during the integration.
3. **Publish**: The customer must publish the container in their GTM account for the tag to be activated. 


### Publishing Your Changes
Data won’t be ingested into Data Cloud until you activate tracking functionality by publishing the GTM container.

After the Data Cloud website connector adds the script tag to your GTM account, complete these steps to activate your connection and start ingesting data. 

1. **Review Changes**: Log in to your Google Tag Manager account and review the changes made to your GTM container.
2. **Publish the Container**: In GTM, create a new version of your container by navigating to the Workspace and clicking `Submit`. Event ingestion won’t start until you publish this new version on your website.
   - Review the Workspace Changes.
   - Add a Version Name and Description for the container update.
   - To publish changes and begin ingesting data into Data Cloud, click `Publish`.