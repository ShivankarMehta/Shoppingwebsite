# Shoppingwebsite

ShoppingSite Project Readme
This is the readme file for the ShoppingSite project, a web application built using Node.js and EJS. The project includes several key features and follows a structured folder hierarchy for organization.

Project Overview
The ShoppingSite project is a simple web application that allows users to browse a list of products, add them to their cart, and manage their shopping experience. Additionally, there is an admin panel for managing products available in the shop.

Features
Shop: Users can view a list of available products in the shop.

Product Details: Users can click on a product to view its details, including price and description.

Cart: Users can add products to their shopping cart, view the contents of the cart, and proceed to checkout.

Add Product (Admin): Admin users can add new products to the shop, including details such as name, price, and description.

Admin Products (Admin): Admin users can view and manage all the products available in the shop, including editing and deleting products.

Folder Structure
The project is structured as follows:

controllers: This folder contains the controller files responsible for handling HTTP requests and responses. Each major feature of the application has its own controller file.

models: The models folder contains JavaScript files that define the data models for the application, such as the Product and Cart models.

views: This folder contains the EJS templates used to render the HTML views for the application. Each major feature typically has its own folder within the views directory.

data: The data folder is used for storing data files or databases that the application relies on, such as JSON files for storing product information.

routes: This directory contains route files that define the URL endpoints and their corresponding controller actions.

public: The public folder is where you can store static assets like stylesheets, images, and client-side JavaScript files.
