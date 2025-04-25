# Mini_Whatsapp


**Project Structure**

- models/
  - chat.js  # Mongoose schema for chat messages
- views/
  - index.ejs  # Displays the list of chat messages
  - new.ejs    # Form to create a new chat message
  - edit.ejs   # Form to edit an existing chat message
- public/
  - (static files)
- app.js       # Main application file



**Routes**

HTTP Method    Route          Description

Get            /chats         View all chat messages

Get          /chats/new       Form to create a new chat

Post         /chats           Create a new chat message

Get          /chats/:id/edit  Form to edit a specific chat

Put          /chats/:id       Update a specific chat message

Delete       /chats/:id       Delete a specific chat message





**Technologies Used**

Backend: Node.js, Express.js

Database: MongoDB, Mongoose

Frontend: EJS (Embedded JavaScript) for templating





**Contributing**

Feel free to fork this repository and submit pull requests to improve the application.




**License
**
This project is licensed under the MIT License.

