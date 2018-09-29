# Project Requirements

Create a bookshelf app that allows you to select and categorize books you have read, are currently reading, or want to read.  The project emphasizes using React to build the application and provides an API server and client library to use to persist information as you interact with the application.

## Functionality

In this application, the main page(the root URL)displays a list of "shelves" (i.e. categories), each of which contains a number of books. The three shelves are:

* Currently Reading
* Want to Read
* Read

![The status page (and completed app) should look something like this](https://user-images.githubusercontent.com/43684522/46240248-6b60e380-c372-11e8-9c55-0d466243c118.png)

Each book has a control that lets you select the shelf for that book. When you select a different shelf, the book moves there. Note that the default value for the control should always be the current shelf the book is in.  

![ss2](https://user-images.githubusercontent.com/43684522/46240256-859ac180-c372-11e8-8be9-31ad8390327e.png)

The main page also has a link to /search, a search page that allows you to find books to add to your library.

The search page has a text input that may be used to find books. As the value of the text input changes, the books that match that query are displayed on the page, along with a control that lets you add the book to your library. To keep the interface consistent, you may consider re-using some of the code you used to display the books on the main page.

![ss3](https://user-images.githubusercontent.com/43684522/46240259-91868380-c372-11e8-972d-3f938dadf9c9.png)

When a book is on a bookshelf, it should have the same state on both the main application page and the search page.

![ss4](https://user-images.githubusercontent.com/43684522/46240262-9ba88200-c372-11e8-9ac3-fbd1a3651a26.gif)

The search page also has a link to / (the root URL), which leads back to the main page.

When you navigate back to the main page from the search page, you should instantly see all of the selections you made on the search page in your library.

## Submission Requirements

Your submission should include all of the files necessary to install and launch your web application on a local web server. For files that include JSX, please refrain from using the .jsx extension (you can prefer .js). You can assume that your reviewer will have npm installed on their machine.