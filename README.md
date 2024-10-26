# Product Management and Shopping Project

Welcome to the Product Management and Shopping project! This project allows users to view products, add products to the cart, adjust quantities in the cart, and search for products.

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Notes](#notes)
- [Contribution](#contribution)
- [Contact](#contact)

## Project Description

This project serves as a simple interface for product management. Users can view all available products, add products to their shopping cart, and adjust the quantities or remove products from the cart. Additionally, users can search for products using the provided search bar.

## Features
- **Product Display:** A list of all available products with their details.
- **Add to Cart:** Ability to add products to the shopping cart.
- **Adjust Quantity:** Users can modify the quantity of products in the cart.
- **Remove from Cart:** Ability to completely remove a product from the cart.
- **Product Search:** A search feature that allows users to quickly find products.

## Technologies Used
- **React:** For building the user interface.
- **Tailwind CSS:** For designing a flexible and beautiful user interface.
- **DaisyUI:** A plugin for Tailwind CSS that provides pre-designed UI components, allowing for faster development and a consistent design.
- **Axios:** Used for making HTTP requests, though primarily the project uses local state for data management.
- **React Router DOM:** For handling routing within the application, enabling smooth navigation between different views.
- **Hamburger React:** A library used for creating a responsive hamburger menu for better navigation on smaller screens.
- **Lucide React:** Provides a set of icons for use throughout the application, enhancing the visual experience.

## Installation

To get started with the project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AhmedAboRaya/Elevate_Task.git
   ```

2. **Navigate into the project directory:**
   ```bash
   cd Elevate_Task
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Run the project:**
   ```bash
   npm run dev
   ```

## Usage

- Once the application is running, you will see a list of available products.
- You can add any product to the shopping cart by clicking the "Add to Cart" button.
- You can adjust the quantity of a product in the cart or remove it entirely.
- Use the search bar to quickly find specific products.

## Notes
While I could have used APIs to handle delete, update, and search operations, I opted to manage data with local state. This choice allows for a more realistic user experience, as using APIs would result in dummy data that lacks authenticity in the add, delete, and other functionalities.

This project is designed to be simple and user-friendly, focusing on the user interface and user experience.

## Contribution
If you would like to contribute to this project, feel free to open an issue or submit a pull request.

## Contact
For any inquiries or feedback, you can reach me at [ahmedaboraya399@gmail.com](mailto:ahmedaboraya399@gmail.com).
