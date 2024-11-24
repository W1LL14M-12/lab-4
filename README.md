In this lab activity, we created a To-Do List API using FastAPI. The API allows you to manage tasks with different actions like adding, updating, getting, and deleting tasks. We worked on two versions of the API: apiv1 and apiv2.

For version 1, we built basic endpoints to handle tasks without security. For version 2, we added security by requiring an API key to access the endpoints, which we stored in a .env file for safety. The API also returns the appropriate status codes for different actions, like 201 when a task is added, and 204 when a task is updated or deleted.

Lastly, we made sure to keep our API key private by using a .gitignore file to avoid uploading it to GitHub. The key was shared privately with the instructor.
