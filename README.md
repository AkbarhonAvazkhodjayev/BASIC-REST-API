# Basic REST API

A simple python program that allows you to post, get, delete, put, and create an authorized user using Postman. These endpoints can be tested through postman. 

```
Features:
-> POST – Create an item with any name and change the price accordingly through postman.
-> GET – Allows you to retrieve all items in the items list, or a specific item in the list.
-> DEL – Delete a specific item in the items list.
-> PUT – Either update or create a new item in the items list.
-> AUTH – Create an authorized user with a unique token. You can apply authentication on any of these 
endpoints and require the user to have a token. 
```


POST request - Creates new item. ![Alt Text](https://github.com/AkbarhonAvazkhodjayev/BASIC-REST-API/blob/master/images/Screen%20Shot%202019-11-20%20at%202.23.54%20PM.png)

&nbsp;

GET request - Retrieves all items.![Alt Text](https://github.com/AkbarhonAvazkhodjayev/BASIC-REST-API/blob/master/images/Screen%20Shot%202019-11-20%20at%202.24.05%20PM.png)

&nbsp;

POST request - Creates an authorized user with token. This token is used to access any encrypted request.![Alt Text](https://github.com/AkbarhonAvazkhodjayev/BASIC-REST-API/blob/master/images/Screen%20Shot%202019-11-20%20at%202.24.17%20PM.png)&nbsp;


GET request - Retrieves specific item and requires authentication for use. Token needed to obtain data.![Alt Text](https://github.com/AkbarhonAvazkhodjayev/BASIC-REST-API/blob/master/images/Screen%20Shot%202019-11-20%20at%202.24.50%20PM.png)



DEL request - Deletes a specific item. ![Alt Text](https://github.com/AkbarhonAvazkhodjayev/BASIC-REST-API/blob/master/images/Screen%20Shot%202019-11-20%20at%202.25.05%20PM.png)

PUT request - Updates or Creates new item. ![Alt Text](https://github.com/AkbarhonAvazkhodjayev/BASIC-REST-API/blob/master/images/Screen%20Shot%202019-11-20%20at%202.25.12%20PM.png)
