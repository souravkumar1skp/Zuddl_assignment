# Zuddl_assignment
Q1. How would your tables and apis change for the following scenarios. What tables and api endpoints would you add? Which tables and api endpoints would need to be updated?
- api endpoints needed are:-
          i. endpoint to save data when new stage is created.
          ii. endpoint to delete data of table when stage(created by user) is deleted.
          iii. endpoint to update data in database when task is completed and slided to another stage.

Q2. If a user can create and edit stages for a particular board. For example instead of Open > In Progress > Done if they want the stages of their task board to be Read > Working > Reviewing > Completed
-  Yes user can create new stages if they want there is extra functionality added to add new board.

Q3. If users can comment on tasks?
- No, but user can add description to the given task which can alternatively serve the purpose.

Q4. How will you do error handling?
  - Display User-Friendly Messages: When an error occurs, display user-friendly error messages. These messages should be clear and concise, helping       users understand what went wrong and how to proceed.
  - Logging: In addition to displaying user-friendly messages, log errors on the client-side for debugging purposes. This can help you identify and       fix issues more easily during development.
  - Use Try-Catch Blocks: Wrap code that might throw exceptions in try-catch blocks. For example, if you're making an API call to the backend             server, place the API call within a try block and catch any potential errors in the catch block.
  - HTTP Status Codes: If your frontend interacts with a backend API, pay attention to HTTP status codes. Different status codes (e.g., 404 for "Not     Found" or 500 for "Internal Server Error") can provide valuable information about the nature of the error.
  - Feedback and Reporting: Allow users to report errors if they encounter issues. This can help you gather information about errors that may not be     caught through automated error handling.
