# Aahar - Food Ordering Application

This is a fully responsive food ordering application that allows users to browse, order, and pay for food items. The application is built using Spring Boot and React.js and includes several key features.

## Features

- **User Authentication**: Users can sign up, create profiles, and log in to the application.

- **Menu Ordering**: Browse through a variety of food items and select items to add to your cart.

- **Shopping Cart**: Users can add and remove items from their shopping cart, specifying quantities.

- **Real-time Notifications**: Utilizing Kafka WebSockets, the application provides real-time push notifications to users.

- **Checkout and Payments**: The application integrates with Stripe for payment processing, enabling users to pay for their orders securely.

- **Order Tracking**: Users can view the status of their placed orders.

## Technologies Used

- **Backend**: Spring Boot
- **Frontend**: React.js
- **DataBase**: MySQL
- **Real-time Communication**: Kafka WebSockets
- **Payment Integration**: Stripe

## Screenshots

Here are some screenshots of the application:

- Home Page
   <img src="https://github.com/jalajbhandula/aahar-foodapp-backend/blob/main/src/main/resources/static/Aahar%20-%20Food%20Application%20Images/Screenshot%20(87).png" alt="Screenshot of the Home Page" width="300" />
  <img src="https://github.com/jalajbhandula/aahar-foodapp-backend/blob/main/src/main/resources/static/Aahar%20-%20Food%20Application%20Images/Mobile%20HomePage.png" alt="Screenshot of the Home Page" width="300" />

- User SignIn Page
  <img src="https://github.com/jalajbhandula/aahar-foodapp-backend/blob/main/src/main/resources/static/Aahar%20-%20Food%20Application%20Images/Screenshot%20(85).png" alt="Screenshot of the Home Page" width="300" />

- User SignUp Page
  <img src="https://github.com/jalajbhandula/aahar-foodapp-backend/blob/main/src/main/resources/static/Aahar%20-%20Food%20Application%20Images/Screenshot%20(86).png" alt="Screenshot of the Home Page" width="300" />

- Menu Page
   <img src="https://github.com/jalajbhandula/aahar-foodapp-backend/blob/main/src/main/resources/static/Aahar%20-%20Food%20Application%20Images/Mobile%20Menu.png" alt="Screenshot of the Home Page" width="300" />
    
- Shopping Cart
   <img src="https://github.com/jalajbhandula/aahar-foodapp-backend/blob/main/src/main/resources/static/Aahar%20-%20Food%20Application%20Images/Mobile%20Cart.png" alt="Screenshot of the Home Page" width="300" />
   <img src="https://github.com/jalajbhandula/aahar-foodapp-backend/blob/main/src/main/resources/static/Aahar%20-%20Food%20Application%20Images/Mobile%20Add%20To%20Cart.png" alt="Screenshot of the Home Page" width="300" />

- Order History
 <img src="https://github.com/jalajbhandula/aahar-foodapp-backend/blob/main/src/main/resources/static/Aahar%20-%20Food%20Application%20Images/Mobile%20Orders.png" alt="Screenshot of the Home Page" width="300" />
 
## How to Run

**Instructions**

```bash
# Clone the repository for backend
git clone https://github.com/jalajbhandula/aahar-foodapp-backend.git
cd food-ordering-app

# Clone the repository for frontend
git clone https://github.com/jalajbhandula/aahar-foodapp-frontend.git
cd food-ordering-app

# Backend setup (if any)
You can use any IDE of your choice to run application such as Spring Tool Suite (STS).

# Frontend setup
cd frontend
npm run dev

# Have Fun and Enjoy the application
