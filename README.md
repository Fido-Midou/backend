# Toronto Sports API

Welcome to our Backend Project! This is a simple **REST API** built with Node.js and Express. It serves data about the major sports teams in Toronto and handles navigation logic.

## Technologies

* **Node.js**
* **Express.js**
* **CORS** (to allow frontend connections)

---

## Instal

1. **Install Dependencies** Open your terminal in this folder and run:
   ```bash
   npm install


## Navigation 

Once the server is running, you can test the navigation by clicking these links or typing them in your browser:

- Get Current Item: http://localhost:[port]/item

- Go to Next: http://localhost:[port]/item/next

- Go to Previous: http://localhost:[port]/item/prev

- Jump to specific Index (e.g., Index 2): http://localhost:[port]/item/2 (You can change 2 to 0, 1, 3, etc.)