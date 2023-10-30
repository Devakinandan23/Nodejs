# Node Farm - README

## Project Overview

Node Farm is a Node.js project that serves as a simple web server for providing information about farm products and their details. It is designed to demonstrate how to create a basic web server using Node.js and handle various types of HTTP requests.

The project includes the following key components:

- A simple web server created using the Node.js `http` module to handle incoming HTTP requests.
- Routing based on URL paths to serve different types of content, including product overviews, individual product details, and a JSON API.
- HTML templates for rendering product information with dynamic data.
- A data file (`data.json`) containing information about various farm products.
- A module (`replaceTemplate.js`) for replacing placeholders in HTML templates with actual product data.

## Project Structure

The project consists of the following main files and directories:

- `server.js`: The main server file responsible for routing and handling HTTP requests.
- `templates/`: Directory containing HTML templates for product overview, product details, and product cards.
- `module/replaceTemplate.js`: A module to replace placeholders in templates with dynamic data.
- `dev-data/data.json`: A data file containing information about farm products in JSON format.

## How to Run the Project

1. Clone the repository to your local machine.
2. Ensure you have Node.js installed.
3. Open a terminal and navigate to the project's root directory.
4. Install project dependencies if necessary: `npm install` (You may need to run `npm install` to install the required packages).
5. Start the Node.js server: `node server.js`.
6. The server will be running at `http://localhost:8000`.

## Usage

### Overview Page

- Access the product overview by visiting `http://localhost:8000/` or `http://localhost:8000/overview`.
- The overview page displays a list of farm products with details and images.

### Product Details

- Access individual product details by visiting `http://localhost:8000/product?id={product_id}`, where `{product_id}` is the ID of the product you want to view.
- Replace `{product_id}` with the actual product ID to view the details of a specific product.

### JSON API

- Access the JSON API by visiting `http://localhost:8000/api`.
- The API provides information about farm products in JSON format.

### Page Not Found

- If you visit an unsupported URL, the server will display a "Page Not Found" message.

## Project Notes

- This is a basic demonstration project, and it can be extended to include more advanced features and functionality.
- Feel free to modify the templates, data, and server logic to suit your own needs or use it as a starting point for building more complex web applications.

Node Farm is a simple example of a Node.js web server project and can serve as a learning resource for those looking to understand the fundamentals of creating web servers with Node.js.
