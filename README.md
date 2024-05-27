# Backend Node Farm

Backend Node Farm is a project to create a simple API using Node.js and the HTTP module. This project provides a basic structure for serving dynamic content from server to client using a web browser.

![Zight Recording 2024-05-27 at 07 58 56 PM](https://github.com/MeltemPinar/Backend-Node-Farm/assets/147662901/e40b0f32-f891-4e22-93b9-3e94f182d2d5)


## Usage

Once the project is successfully installed, you can start the application using the following command:

npm start

This command will start an HTTP server on port 8003 at address 127.0.0.1. You can then send requests to URLs like http://127.0.0.1:8003/overview and http://127.0.0.1:8003/product?id={product_id} using your browser or an API testing tool.

## API Paths

/overview: Provides a general overview of the products.

/product?id={product_id}: Provides details of a specific product. The {product_id} parameter specifies the identifier of the desired product.

