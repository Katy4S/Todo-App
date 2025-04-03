React Todo App with API


This is React Todo App with API project, the functionality has been extended to include toggling and renaming todos, in addition to the existing add and delete features.
The application demonstrates API integration with React and TypeScript, providing a smooth user experience with real-time updates and error handling.


This project is a fully functional Todo application that allows users to:

Toggle a Todo's Status:
Click on a todo to toggle its completion status. A loader overlay is displayed while waiting for the API response. On success, the updated status is applied, and if an error occurs, a notification is shown.

Toggle All Todos:
Use the toggleAll checkbox to update the status of all todos at once. The toggleAll button gets an active class only if all todos are completed. The status of each todo is updated individually, but API calls are only sent for those that actually change.

Rename a Todo:
Double-click on a todo to switch into edit mode. You can update the title by pressing Enter or by losing focus (onBlur). If the new title is the same as the old one, the edit is canceled; if it’s empty, the todo is deleted. Loader overlays and error notifications are also managed for renaming actions.



Demo
🔗 Live Preview

Technologies Used
React
TypeScript
HTML / SCSS
JavaScript


Getting Started
Follow these steps to set up the project locally:

Prerequisites
Node.js (version 14 or above recommended)

npm or yarn

Installation
Clone the Repository:

git clone https://github.com/Katy4S/Todo-App.git
cd react-todo-app-api


Install Dependencies:
npm install or yarn install

Run the Project Locally:
npm start or yarn start

