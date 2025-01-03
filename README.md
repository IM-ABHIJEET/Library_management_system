# Library Management System Front End <img src="assets/icon.png" alt="header-logo" width="27px"/>

This project was bootstrapped with [Create React App]

This is the **React Front End** of the **library management system.** Highlighted features of the system is as follows,

- Members are registered to the system by [**UUID**](https://en.wikipedia.org/wiki/Universally_unique_identifier), and no two members can have the same contact number.
- Books are registered to the system by international standard book number (isbn).
- When members take books from the library they will receive an issue note.
- The issue note contains all the take away book ISBNs along with the member UUID.
- All issue notes have unique issue id to uniquely identify them when the books are returned.
- Issue note can only have maximum 3 distinct ISBNs.
- A member cannot take the same book from the system twice at the same time or at two different times (with another issue note).
- A member can only take maximum of 3 different books from the system. If he/she needs another, he/she must return a book that he/she already got.


#### Images of the User Interfaces

1. Dashboard<br>
   <img src="assets/dashboard.png" alt="dashboard" width="700px"/>

2. Manage Members<br>
   <img src="assets/manage_members.png" alt="manage-members" width="700px"/>

3. Manage Books<br>
   <img src="assets/manage_books.png" alt="manage-books" width="700px"/>

4. Issue Books<br>
   <img src="assets/issue_books.png" alt="issue-books" width="700px"/>

5. Handle Returns<br>
   <img src="assets/handle_returns.png" alt="handle-returns" width="700px"/>











## Used Technologies

- React
- MUI
- TypeScript
- React Router
- Axios


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\


The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!


### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.


