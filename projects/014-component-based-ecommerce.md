# Project: Component-Based E-commerce Product Display

## Project Overview
In this project, you will create a simple component-based interface for an e-commerce product display page. This project focuses on componentization, state management, and setting a foundation for framework-based applications.

### Key Features

1. **Component-Based Structure**
   - **ProductCard Component**: Display individual product details such as image, name, price, and "Add to Cart" button.
   - **ProductList Component**: Render a list of ProductCard components, which will update based on user actions.
   - **Cart Component**: Display selected products with options to adjust quantity or remove items.

2. **State Management**
   - **Product State**: Manage product data and ensure that products are passed to the ProductList and ProductCard components.
   - **Cart State**: Track items added to the cart and allow users to manage items within the Cart component.

3. **Real-time Updates (Simulated)**
   - Implement changes to the Cart component state to reflect real-time updates when items are added or removed.

4. **Reusable & Modular Components**
   - Use reusable, modular components to build a scalable and maintainable code structure.

### Learning Objectives
- Understand the concept of component-based architecture and its benefits.
- Implement basic state management for components.
- Create a responsive UI by dynamically rendering components based on state changes.

### Technologies
- **HTML** and **CSS** for layout and styling.
- **JavaScript (ES6)** for component functionality and state management.

---

## Project Steps

1. **Create a ProductCard Component**
   - This component should display product details (image, name, price).
   - Include an "Add to Cart" button that, when clicked, updates the cart state.

2. **Develop the ProductList Component**
   - Render multiple ProductCard components in this component.
   - Fetch product data and use it to populate each ProductCard with details.

3. **Build the Cart Component**
   - Display products added to the cart, along with their quantities.
   - Implement functionality to update quantities or remove items.

4. **Manage State**
   - Use JavaScript to manage both product and cart state, ensuring that changes in one component (like adding to cart) are reflected in others.

5. **Style the Components**
   - Use CSS to style the components, creating a responsive layout for the product display and cart.

6. **Bonus Features**
   - Display a total price in the Cart component.
   - Enable quantity adjustments for each cart item.
   - Add filtering options in the ProductList component (e.g., filter by price or category).
