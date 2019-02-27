# Page Generator

Using the provided files, create a script that dynamically generates a page based on JSON data.

## Getting started
1. `npm install`
2. `npm start`
3. View `localhost:3000/index.html`, which hot-reloads.

## Steps to complete

### Mock API response

You should create a mock API response JSON body, placed inside of the `page-generator.js` file as `const DATA`. **You do not need to adhere to JSON styling**, feel free to use single quotes and the like. **This API response should control the HTML of the page**. It is the source of truth for what is rendered inside of `<div id="app"></div>`.

### Create render function

Create a function that takes the API JSON response and renders elements from it. This function **accepts the API response as the source of truth for HTML layout**.

#### Do your work in `page-generator.js`

## Other files (don't need to touch these)
- **index.html**: HTML entry file.
- **index-complete.html**: **Example only!** This shows you approximately what your generator should output. You can view it at `localhost:3000/index-complete.html`.
- **style.css**: Styling. You don't need to worry about this.
