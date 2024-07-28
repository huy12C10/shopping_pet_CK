Project: Pet Shop
1. Project Overview:
- Front-end:
  + Built with React.js.
  + User interface
  + Interacts with the server API
- Back-end:
  + Built with Node.js.
  + Handles server-side logic
  + Manages the database
  + Provides API for the front-end
- Database: MongoDB
- API Testing: Postman
2. Website Features:
- Admin:
  + Login and Logout
  + Add Category and Product
  + View list of Category, Product, Order, and Customer
  + Update Category, Product, and Order Status
  + Delete Category and Product
  + Send activation and deactivation emails to Customers
- Customer:
  + Home
  + Sign up, Activate, Login, Logout, and My Profile
  + Search, Details
  + Add to cart, My cart, Remove from cart
  + Checkout, My orders
  + Access token
- Other: Responsive, use of modals
3. References:
- Modal and hide/show password guide: https://www.youtube.com/@hoidanit
- Bootstrap V5: https://getbootstrap.com/docs/5.0
- Building Footer: https://www.youtube.com/watch?v=f0bmU_Ponyk
- Sass documentation: https://topdev.vn/blog/sass-scss-la-gi/
4. Instructions to Run the Project:
- Navigate to the server directory:
+ cd server (Build the project (install node modules for admin and customer))
-> npm build ("build": "(npm install) && (cd ../client-admin && npm install && npm run build) && (cd ../client-customer && npm install && npm run build)")
+ Start the project:
-> npm start ("start": "node index.js")
- Connect to MongoDB: mongodb+srv://long:1234@shopping.rzqoj6m.mongodb.net/
- Admin:
 + User: long
 + Password : 123
