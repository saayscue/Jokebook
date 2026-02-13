### MVC App

Jokebook is a simple MVC web app built with Node.js, Express, and EJS that lets users store, browse, and get jokes organized by category. It shows basic Create, Read, and Search functionality: add jokes (use categories `lameJoke` or `funnyJoke`), view jokes by category, search by category, and fetch a random joke.

### Installation

- Get the project
  - download zip
  - clone

- Open the project in VSCode.
- Open a Terminal.
- Install required packages.

```
npm install
```

- Start the server

```
nodemon server.js
```

- After starting the server, go to the landing page

```
http://localhost:3000
```

- When adding a new joke, in the category box type either

```
lameJoke
```

or

```
funnyJoke
```

When all the boxes are filled, click save and then the new joke will be shown along with the other jokes in that category.

- Get a random joke by clicking on the "Get a new random joke" button.

- In the search bar, type either

```
lameJoke
```

or

```
funnyJoke
```

- You can also click on one of the category names to get the jokes responding to the category too.
