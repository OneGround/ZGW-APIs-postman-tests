# Oneground Postman Tests

This repository contains two Postman collections for ZGW (Zaakgericht Werken). One is for validating business rules and one is for sample case creation. 

## Contents

- `ZGW business rules.postman_collection.json`  
  Postman collection for testing ZGW business rules.
- `ZGW business rules.environment.json`  
  Environment configuration for the business rules tests.
- `ZGW Create Case.postman_collection.json`  
  Postman collection creating sample cases.
- `ZGW Create Case.environment.json`  
  Environment configuration for case creation.

## Usage
To use these collections, you need to have [Postman](https://www.postman.com/) installed on your computer. Postman is available for Windows, macOS, and Linux.

1. **Import Collections and Environments**
   - Open Postman.
   - Click `Import` and select the relevant `.postman_collection.json` and `.environment.json` files.

2. **Configure Environment Variables**
   - After importing, select the appropriate environment (Business Rules or Create Case). Especially - add the ClientID and secret
   - Update variables (such as API base URLs, authentication tokens, etc.) as needed for your setup.

3. **Run Project**
   - Select the desired collection.
   - Click `Run` to execute all requests in the collection, or run individual requests as needed.
   - Review  results in the Postman runner or in the response tabs.



## Support
Email support@oneground.nl or create an issue: [GitHub Issues](https://github.com/OneGround/ZGW-APIs/issues)
