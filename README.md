
## How to run

### Frontend
To start the front-end go into the frontEnd folder:

```bash
cd frontEnd
```

And then start it with:

```bash
npm run dev
```

### Server
To run the server go to the server folder:

```bash
cd server
```
And then start it with:

```bash
npm start
```


## Documentation
For the project realization the following technologies have been used:

- ReactJS
- React Router (for a SPA approach)
- Axios (to better handle API calls and errors)

### About the functionalities

#### Main Page
<img  src="https://github.com/J0hnnyGee/interviews-front-end-assignment/blob/main/frontEnd/public/Main%20page.png"/>

The main page is made of three main components:
- Navbar
- Recipe List
- Sidebar

#### Navbar
Through the navbar thanks to react routing is possible to visit the webapp's pages using a single-page-application approach.

#### Recipe List 
The recipe list is showing as default the whole dateset of recipes present in the given API, divided in groups to reduce the browser load. 
Is possible to see the other recipes using the buttons at the bottom.

#### Sidebar
The sidebar makes possible for the use to filter the shown recipes using the given fields.
To make less possible for the user to make errors, and to get a more modern UI, for all the field exept the name it has been chosen to show some selectable options or a slider.

#### Add Recipe
<img  src="https://github.com/J0hnnyGee/interviews-front-end-assignment/blob/main/frontEnd/public/Add%20recipe%20page.png"/>

Through the "Add" button of the Navbar is possible for the user to visit the Add recipe page.
Here the user can add all the details of his favourite recipe.

Some important details for this section are:
- It's possible to load an image, see it, and delete it.
- It is possible to add and delete recipe ingredients
- A maximum of four ingredients are shown to avoid crowding the interface


### Future implementations
The webapp here shows some basic functionalities, but here I would like to give some possible future implementations:
- A working add recipe operation (at the moment only in UI)
- A recipe detail page
- A profile page
- The chance for the user to save his favourite recipes
- Some animations to make the UX more enjoyable
- Filter the recipes by category
- A more robust error handling and responsiveness

