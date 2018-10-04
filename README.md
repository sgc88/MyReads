# MyReads Project
[Udacity's](https://www.udacity.com/) Nanodegree *MyReads* Project. This app can help you keep organized with your book reading.

## Getting Started
- *Download* or *Clone* this repo to your local machine.
- ```cd``` into the project.
- Install all project dependencies with ```npm install```.
- Start the development server with ```npm start```.

## User Stories
- A user can go to the main page and see *three* bookshelves:
	- *currently reading*
	- *want to read*
	- *read*
- A user will see books displayed with its *title* and *author(s)*.
- A user is able to move books between *shelves*.
- A user is able to *refresh* the browser and see the same books displayed on the page.
- A user can proceed to the *search* page and use the *search input* to search for books.
- As a user types into the *search field*, books that match the query will be displayed on the page.
- When a user leaves the *search field* empty **no** search results will be shown.
- A user is able to search for *multiple words*, i.e. "artificial intelligence".
- A user is able to *categorize* a book from the *search page*.
- A user's selections made on the *search page* show up on the *main page*.
- A user is successfully sent to the *main page* from the link in the *search page*.

## Technologies Used
-	[react.js](https://reactjs.org/)
-	[react-router-dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)
-	[create-react-app](https://github.com/facebook/create-react-app)

## Search Terms
 The provided backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](https://github.com/kepelrs/MyReads/blob/master/SEARCH_TERMS.md). That list of terms are the _only_ terms that will work with the backend, so don't be surprised if your searches for Basket Weaving or Bubble Wrap don't come back with any results.
