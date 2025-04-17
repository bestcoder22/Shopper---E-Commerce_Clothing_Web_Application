# Shopper - E-Commerce Clothing Web Application
Shopper is a dynamic e-commerce web application designed for a clothing store, built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application includes fully responsive sections for Men, Women, and Kids, allowing users to browse a product catalog, manage a shopping cart, and securely register or log in.

The admin panel, built with Vite, provides functionality for managing the product database — including adding, removing, and viewing products in real-time. The cart system automatically calculates total price and preserves cart items during sessions, reducing cart abandonment and enhancing the user experience.

RESTful APIs were developed to optimize database interactions, reducing MongoDB query times by 25%, and improving CRUD operation efficiency.

## Key Features
- Responsive product catalog for Men, Women, and Kids.

- Secure user registration and login.

- Shopping cart with real-time updates and automatic total price calculation.

- Persistent user sessions to reduce cart abandonment.

- Admin panel (built with Vite) for adding, removing, and viewing products.

- RESTful APIs for efficient CRUD operations on MongoDB.

- Improved performance with optimized query handling.

## Table of Contents


- [Installation](#installation)
  - [Clone Repository](#clone-repository)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
  - [Admin Panel Setup](#admin-panel-setup)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Contact](#contact)

## Installation

### Clone Repository
Clone the repository using the following command:
```bash
git clone https://github.com/bestcoder22/Shopper---E-Commerce_Clothing_Web_Application.git
```

### Backend Setup
1. Navigate to the Backend directory:
   ```bash
   cd Backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

4. Configure the Database:

- Create a MongoDB Atlas database (or use a local MongoDB instance).

- Update the connection string in the server.js file as shown below:

```javascript
const uri = "mongodb+srv://<username>:<password>@cluster.mongodb.net/<database-name>";
```

4. Run the Backend Server:
   ```bash
   node server.js
   ```
The backend server will run on http://localhost:4000.

### Frontend Setup

1. Navigate to the Frontend directory:
   ```bash
   cd Frontend
   ```


2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the React development server:
   ```bash
   npm start
   ```
The frontend will run on http://localhost:3000.

### Admin Panel Setup

1. Navigate to the Admin Panel directory:
   ```bash
   cd AdminPanel
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the Admin Panel using Vite:
   ```bash
   npm run dev
   ```
   The admin panel will run on http://localhost:5173.

### Usage

- User Functionality:
  - Browse and filter products by Men, Women, and Kids categories.
  - Add products to the cart, view total pricing, and complete secure transactions.
  - User registration and login features protect the user data and session.

- Admin Functionality:
  - Manage products by adding or removing items.
  - View the entire product list from the database.
  - Monitor active sessions and cart persistency in real-time.

### Screenshots

- Home Page
  ![Screenshot 2025-04-17 133411](https://github.com/user-attachments/assets/1bdbbfe9-45c3-442e-a3ef-875c92640282)

- Men Section (similarly for womens and kids section)
  ![Screenshot 2025-04-17 133443](https://github.com/user-attachments/assets/5e65126a-be0f-4392-ac9c-2dbc6669e509)

- Login Page
  ![Screenshot 2025-04-17 133516](https://github.com/user-attachments/assets/6fd573f6-6702-4d85-9f63-81e8472c53d4)

- Cart Section
  ![Screenshot 2025-04-17 133538](https://github.com/user-attachments/assets/0fcda961-05f0-4838-b253-706497143b64)

- Admin Panel
  ![image](https://github.com/user-attachments/assets/7850a730-d7ad-4b5b-9dfc-d5b29199711f)

### Technologies Used

- Frontend : React.js
- Backend : Node.js, Express.js
- Database : MongoDB
- Admin Panel : Vite

### Contact

For any inquiries or feedback, please contact:
- Email : amrutkarsoham22@gmail.com
- Github Username : bestcoder22





