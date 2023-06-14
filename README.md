# Project Name

This project is a React application that includes several components for a shopping and blogging website. Below is a description of each folder and component in the project.

## Chakra UI

Chakra UI is a simple and modular component library that provides a set of accessible and customizable UI components for React. It follows a design system approach, making it easy to create consistent and visually appealing user interfaces.

To learn more about Chakra UI, you can visit the official documentation:    (https://chakra-ui.com/)


## Folders

### App

This folder contains the main component that sets up the routing for different pages of the application using `react-router-dom`.

### Cart

This folder contains the `Cart` component that represents a shopping cart view. It uses Chakra UI components to display the items in the cart, along with their prices and total cost.

### Home

This folder contains the `Home` component that represents the home page of the application. It renders multiple instances of the `PostCard` component within a grid layout using Chakra UI's `Container` and `Grid` components.

### PostCard

This folder contains the `PostCard` component that represents a card displaying a post. It contains information such as the author, post content, and a button to view the full post.

### PostPage

This folder contains the `PostPage` component that represents a page displaying a full post. It includes the post title, image, author information, post content, and an accordion component for additional sections.

### Navigation

This folder contains the `NavBar` component that represents the navigation bar at the top of the application. It includes a menu button for opening a drawer (side menu) and an avatar for user profile access.

### YourDetails

This folder contains the `YourDetails` component that represents a form for entering user details, such as first name, last name, address, city, and country. It includes Chakra UI form components for input fields, checkboxes, and buttons.

## Components

### App

This is the main component that sets up the routing for different pages of the application using `react-router-dom`. It renders the `NavBar` component and defines routes for the `Home`, `PostPage`, and `CartPage` components.

### Cart

This component represents a shopping cart view. It uses Chakra UI components to display the items in the cart, along with their prices and total cost.

### Home

This component represents the home page of the application. It renders multiple instances of the `PostCard` component within a grid layout using Chakra UI's `Container` and `Grid` components.

### PostCard

This component represents a card that displays a post. It contains information such as the author, post content, and a button to view the full post.

### PostPage

This component represents a page that displays a full post. It includes the post title, image, author information, post content, and an accordion component for additional sections.

### NavBar

This component represents the navigation bar at the top of the application. It includes a menu button for opening a drawer (side menu) and an avatar for user profile access.

### YourDetails

This component represents a form for entering user details, such as first name, last name, address, city, and country. It includes Chakra UI form components for input fields, checkboxes, and buttons.
