* **Files**

  * `22-CatsAppProblem`

* **Instructions**

  * Add a delete button into the `index.handlebars` file next to each cat.

  * Add on to the following:

  * The `cats.js` file to add a jQuery event handler for the delete button.
  * The ORM to include a delete key and function
  * The cat model to include a delete key and function that uses the ORM
  * The `catsController.js` file to have a `/api/cats/:id` delete route, to call the delete key of the cat model, and to pass in arguments as necessary


* **Files**

  * `17-CatsAppProblem`

* **Instructions**

  * Add a delete button into the `index.handlebars` file next to each cat.

  * Add on to the following:

  * The `cats.js` file to add a jQuery event handler for the delete button.
  * The ORM to include a delete key and function
  * The cat model to include a delete key and function that uses the ORM
  * The `catsController.js` file to have a `/api/cats/:id` delete route, to call the delete key of the cat model, and to pass in arguments as necessary


* **Place to jump off from**

  1. add delete button -- just a form with a submit
  2. create a delete route -- have it delete nothing, but redirect to /
  3. add ORM delete function -- does nothing, just calls back (call the callback)
  4. add actual delete functionality