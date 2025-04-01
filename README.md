# 📱 React Phone catalog 📱

<p>A brief description of the project
Implement landing page according to Figma design</p>

# [Design](https://www.figma.com/file/uEetgWenSRxk9jgiym6Yzp/Phone-catalog-redesign?node-id=1%3A2)

## Description

<p>Simple responsive internet-shop with favorites, cart, search, slider. Done with React Context, router-dom, axios etc. I made a simple node js backend which always returns the same data, provided for the catalog.</p>

# [Demolink](https://pokhvalenkos.github.io/phone-catalog/)

## 📚 Technologies Used

- **React**: JavaScript library for building user interfaces with reusable components
- **React Router**: Library for routing in React applications
- **Sass**: CSS pre-processor for writing more maintainable styles
- **Webpack**: Module bundler to compile the project
- **TypeScript**: Superset of JavaScript that adds static typing
- **Redux Toolkit**: A library for efficient state management in React applications
- **Swiper**: A modern, mobile-friendly touch slider for implementing interactive carousels
- **Node.js & npm**: Environment and package manager for managing dependencies

# React phone catalog features:

- Main data storing is realized through react context.

- Cart stores in Local Storage.

- React-router-dom and urlParams are widly used.

- You can sort a list of products.

- There are the breadcrumbs.

- A few sliders exist. Main with timer and steering buttons and two more, smaller.

- Search is working with debounce and stores in url.

- Cart total sum is shared among every item and works well, what is amazing.

- Pagination is customizible by setting amount of items on page.

## 🚀 How to run the Apps.

### Pre-requirements

You need [`Node`](https://nodejs.org/es/) previously installed in your computer.
To start using this project, clone this repo to a new directory.

### ➡️ Node

You have to go to server and run npm install in order to install the necesary dependencies.

#### - Server

General Environment variables (server side):

> ```console
> PORT=5005
> ORIGIN=http://localhost:3000
> ```
>
> Console:
>
> ```console
> $ cd server
> $ npm install
> ```

Now you need to do the same thing on the client side.
Environment variables:

> ```console
> REACT_APP_SERVER_URL=http://localhost:5005
> ```

Console:

> ```console
> $ cd client
> $ npm install
> ```

Once you have installed the dependencies, you are ready to run the app with `npm start`. Like above, we need to do it both in server and client sides.

Server Side:

> ```console
> $ cd server
> $ npm run dev
> ```

Client side:

> ```console
> $ cd client
> $ npm start
> ```

> 👉 Open http://localhost:3000 to view in the browser
