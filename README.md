# Food Ordering and Tracking Chatbot
![Food Chatbot Screenshot](https://raw.githubusercontent.com/jothsnapraveena/food_ChatBot/master/Screenshot%202025-01-06%20202212.png)

This project implements a conversational chatbot using Dialogflow to facilitate food ordering and order tracking. The chatbot assists users in placing new orders for food items and provides features to track the status of their orders.
In my current implementation, I've employed ngrok to expose my local server to a public URL, facilitating testing and development. However, it's important to acknowledge that the limited version of ngrok ceases the tunnel upon closure of both the command prompt and the Python process
## Features

- **Order Placement**: Users can interact with the chatbot to place new orders for food items from available restaurants.
- **Order Tracking**: Users can inquire about the status of their existing orders and get real-time updates on the progress.
- **Natural Language Understanding**: Dialogflow is utilized to understand user queries and intents, enabling a conversational interface for order placement and tracking.
- **FastAPI Backend Server**: A FastAPI backend server interacts with the Dialogflow agent and manages order information in a MySQL database.
- **MySQL Database**: Stores information about orders, including order details, status, delivery information, etc.

## Tech Stack

- **Dialogflow**: Dialogflow serves as the natural language understanding platform, enabling the chatbot to comprehend user intents and respond accordingly.
- **MySQL Database**: MySQL is employed to persistently store order data, allowing for efficient retrieval and management of order information.
- **FastAPI**: FastAPI powers the backend server, providing RESTful API endpoints for communication with the Dialogflow agent and interaction with the database.
- **Python**: Python is the primary programming language used for implementing the FastAPI backend server, integrating with Dialogflow, and managing order-related functionalities.



## Usage

- Users can interact with the chatbot via any platform integrated with Dialogflow (e.g., web, mobile app, Google Assistant, etc.).
- To place a new order, users can specify the food items they wish to order, provide delivery information, and confirm the order details.
- Users can inquire about the status of their existing orders by asking the chatbot for order updates.



## Acknowledgements

- Special thanks to Dialogflow, FastAPI, and MySQL for providing excellent tools and technologies for building this chatbot project.
- Thanks to @ Dhaval Patel,codebasics

