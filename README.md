Shopping list v5
================

[![Build Status](https://travis-ci.org/KliCk5000/node-shopping-list-integration-tests.svg?branch=master)](https://travis-ci.org/KliCk5000/node-shopping-list-integration-tests)

https://github.com/Thinkful-Ed/node-shopping-list-v5

* Serves client that:
    + makes AJAX calls back to API endpoints to initially retrieve and display existing recipes and shopping list.
    + allows users to add, check/uncheck, and delete shopping list items
    + allows users to add and delete recipes
* Uses `express.Router` to route requests for `/recipes` and `/shopping-list` to separate modules.
* CRUD (create, read, update, delete) operations for recipes and shopping list
* Note: uses volatile, in memory storage, since we haven't studied data persistence yet in the course.