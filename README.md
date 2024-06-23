# Baptiste Farm Ecommerce Platform

## Project Overview
The Baptiste Farm Ecommerce Platform is a web application designed to facilitate the online sale of products produced by Baptiste Farm. These products include baby chickens, Tilapia fingerlings, and Italian honey bee nucs. The platform is built using Magento for backend ecommerce functionalities and React for the frontend user interface, all hosted on AWS for scalability and reliability.

## Features
### User Authentication
- **User Registration**: Users can create an account to shop and track orders.
- **User Login**: Registered users can log in to access their accounts.
- **Password Recovery**: Users can reset their passwords if forgotten.
- **User Logout**: Users can securely log out of their accounts.

### Product Listings
- **Product Categories**: Products are organized into categories (Baby Chickens, Tilapia Fingerlings, Italian Honey Bee Nucs).
- **Product Details Page**: Each product has a detailed page showing its description, price, and availability.
- **Search and Filter**: Users can search for products and apply filters to narrow down the options.

### Shopping Cart
- **Add/Remove Products**: Users can add products to their cart and remove them if needed.
- **View Cart Summary**: Users can view a summary of the items in their cart, including the total price.
- **Update Quantities**: Users can change the quantities of products in their cart.
- **Proceed to Checkout**: Users can proceed to checkout to finalize their purchase.

### Payment Integration
- **Support for Multiple Payment Gateways**: The platform integrates with Stripe and PayPal for secure payments.
- **Credit/Debit Card Support**: Users can pay using their credit or debit cards.
- **Payment Confirmation**: Users receive confirmation of their payment and order details.

### Order Management
- **Order Placement**: Users can place orders for products in their cart.
- **Order Tracking**: Users can track the status of their orders from placement to delivery.
- **Order History**: Users can view their past orders and their details.

### User Profiles
- **Personal Information Management**: Users can view and update their personal information.
- **Order History**: Users can view their order history and reorder products if desired.
- **Address Management**: Users can manage their shipping addresses.

## Project Architecture
The project architecture leverages AWS services for hosting and scalability.

### Components
1. **Frontend**: React application hosted on AWS S3 and delivered via CloudFront.
2. **Backend**: Magento hosted on an AWS EC2 instance.
3. **Database**: MySQL database hosted on Amazon RDS.
4. **Storage**: Amazon S3 for storing static assets like product images.
5. **CDN**: Amazon CloudFront for content delivery.

![High-Level Architecture Diagram](sandbox:/mnt/data/A_high-level_architecture_diagram_for_a_simple_eco.png)

## Database Schema
The database schema includes tables for users, products, orders, order items, and payments. Each table is designed to store relevant data and maintain relationships with other tables.

![Database Schema Diagram](sandbox:/mnt/data/A_clear_and_detailed_database_schema_diagram_for_a.png)

## Getting Started
To get started with the development and deployment of the Baptiste Farm Ecommerce Platform, follow these steps:

1. **Set Up AWS Account**: Create and configure an AWS account.
2. **Deploy Magento**: Launch an EC2 instance, install Magento, and configure it with RDS MySQL.
3. **Deploy React Frontend**: Host the React application on S3 and set up CloudFront.
4. **Configure Storage and CDN**: Use S3 for static assets and CloudFront for CDN.

## Development Roadmap
### Week 1: Planning, Setup, and Initial Development
- **Day 1-2**: Planning and requirement gathering.
- **Day 3-7**: Initial AWS setup and Magento configuration.

### Week 2: Backend Development and Frontend Setup
- **Day 1-3**: Magento backend customization.
- **Day 4-7**: React frontend development.

### Week 3: Integration and Testing
- **Day 1-3**: Integrate frontend with backend.
- **Day 4-7**: Testing and debugging.

### Week 4: Finalization and Deployment
- **Day 1-3**: Finalize features and optimizations.
- **Day 4-7**: Deployment and launch.

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests for review.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any inquiries or support, please contact [your email].