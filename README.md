## Introduction
This collection for Postman included requests to test Trello application.
In this collection we have the following requests: 
- Get a member (Method GET)
- Create new board (Method POST)
- Create new list (Method POST)
- Create new card (Method POST)
- Update card name (PUT)
- Delete a Board (DELETE)
- Get a Board (GET)

Requests all include best practices and script to tests. For example, I used the below scripts: 

- Pre-request (Generating a random data for tests, saving a value to collection variables, re-using a variable in the next requests)
- Post-response (Checking if status code has a correct after sending)

Collection is based on documentation for [Trello API](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions)

## Important information 
In this collection, I generated AUTH_KEY and TOKEN for authorization to the Trello API. 
Both AUTH_KEY and TOKEN expire after 14 days. To, use the collection you need to generate a new key and token.

You can use from this instruction: https://developer.atlassian.com/cloud/trello/guides/rest-api/authorization/


## Technologies:
- [Postman](https://www.postman.com/downloads/)


## How to start:
1. Install [Postman](https://www.postman.com/downloads/)
2. Log in using existing account or create a new account in Postman
3. Import this collection [Import Collection](https://learning.postman.com/docs/getting-started/importing-and-exporting/importing-data/)
4. You can executing all requests from this collectiom to test Trello Board


