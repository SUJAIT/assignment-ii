
# 📚 Book & Order Management API
This Project backend api built with Nodejs,Expressjs,typScript and MongoDB. The users to manage books and handle orders, including creating, updating, retrieving, and deleting records are created using Simple CRUD Operation in this Api.It also provides functionality to calculate total revenue for orders ,This Api created Use MongoDB aggregation pipeline.
#

# ✨ Features
📘 Book Management

* Create Book: Add new books with details like title, author, price, category, description, quantity, and stock status.
* Retrieve All Books: Fetch a list of all available books.
* Retrieve Specific Book: Get detailed information about a specific book by its ID.
* Update Book: Update the details of an existing book by its ID.
* Delete Book: Remove a book from the system by its ID.

🛒 Order Management

* Place an Order: Create a new order for a specific book with quantity and total price.
* Revenue Calculation: Calculate the total revenue generated from all orders.

#
# 🛠️ Technology Stack
* Language: TypeScript
* Framework: Express.js
* Database: MongoDB
* (ODM)library: Mongoose

* Other Tools: 
     * ts-node-dev for development with TypeScript
     * dotenv for environment variable management

     * eslint and prettier for code linting and formatting

# 
# API Endpoints



## 📘 Books


```http
  GET /api/items
```

| Method | Endpoint     | **Description** |
| :-------- | :------- | :------------------------- |
| `POST` | `/api/products` | Create a new book |
| `GET` | `/api/products` | Get all books |
| `GET` | `/api/products/:productId` | Get a specific book |
| `PUT` | `/api/products/:productId` | Update a specific book |
| `DELETE` | `/api/products/:productId` | Delete a specific book |


### 🛒 Orders

|Method|Endpoint|Description|
| :-------- | :------- | :-------------------------------- |
| `GET`| `/api/orders` | Place a new order |
| `POST`| `/api/orders/calculate` | Calculate total revenue |

#### Projects Related All Links :
* GitHub Repository Link :
```http
 https://github.com/SUJAIT/Assignment-Two.git
```
* Live Deployment Link  :
```http
assignment-two-blue.vercel.app
```
* Video Explanation (Public Link) :

```http
assignment-two-blue.vercel.app
```
* Professional README file Link :
```http
assignment-two-blue.vercel.app
```
