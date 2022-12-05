# National-Railways-API_Mulesoft
 *Send train delay notifications to the passengers with user authentication*
## Features
- To build a secured authentication application, the nation-Railway application is secured with [Okta](https://developer.okta.com/docs/reference/postman-collections/).
- User data, alerts details, alert history is stotred in **MySQL Database**.
- [Json Logger](https://blogs.mulesoft.com/dev-guides/how-to-tutorials/json-logging-mule-4/) is added to log the status of the applications.
- [Splunk](https://dzone.com/articles/recipe-to-implement-splunk-enterprise-on-premise-f) is embeddded in the log4j.xml logging, analyzing and reporting. Where we can search the status of the application.
- Created all the error handling tickets in [service now](https://www.royalcyber.com/blog/middleware/mulesoft/mulesoft-integration-with-servicenow-and-salesforce-service-cloud/) which is integarted with the mulesoft **error.xml**.
- Encrypted the sensitive data from **config.xml** using secure properties.
- Extracted Data from National Railways [SOAP API](https://github.com/mattsalt/national-rail-darwin) 
to compare with the notification alert that are requested by the authenticated user with [Okta](https://developer.okta.com/docs/reference/postman-collections/).

# Learn More
- [Mulesoft Docs](https://docs.mulesoft.com/general/) - Learn about muleosft connecters and API.
- [RAML Docs](https://raml.org/developers/document-your-api) - Learn how to build RAML in to design how an API looks like. 
- [Mulesoft Training](https://training.mulesoft.com/course/development-fundamentals-mule4-bootcamp) - Learn the fundamentals of Anypoint Platform and mulesoft. 