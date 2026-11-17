# Experiment 8 - Book API (Node.js + Express.js)

RESTful API for a book collection (CRUD, in-memory data).

## Run locally
```
npm install
npm start
```
Open http://localhost:3000/books

## Endpoints
| Method | URL | What it does |
|--------|-----|--------------|
| GET | /books | list all books |
| GET | /books/:id | get one book |
| POST | /books | add a book (JSON body: title, author) |
| PUT | /books/:id | update a book |
| DELETE | /books/:id | delete a book |
