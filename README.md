# SwiftCart

SwiftCart is a modern e-commerce application built with Svelte for the frontend and designed to provide users with a seamless shopping experience. This project allows users to browse products, filter them by categories, search for specific items, sort by price, and view detailed information about each product.

## Technologies Used

- **Svelte**: A modern JavaScript framework used for building the user interface.
- **Svelte-Routing**: Provides routing capabilities for navigating between different views in the application.
- **Tailwind CSS**: A utility-first CSS framework used for styling the application.
- **API**: Fake Store API (`https://fakestoreapi.com`) for fetching product and category data.

## Setup Instructions

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**
- **npm** 

### Clone the Repository

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/swiftcart.git
   ```

2. Navigate to the project directory:

   ```bash
   cd swiftcart
   ```

### Install Dependencies

1. Install the necessary dependencies using npm or yarn:

   ```bash
   npm install
   ```

### Run the Development Server

1. Start the development server:

   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:5000` to view the application.

### Build for Production

1. To build the application for production, run:

   ```bash
   npm run build
   ```

2. The production build will be output to the `public` directory, and you can deploy it to your preferred hosting service.

## Usage Examples

### Navigation

- **Home Page**: Displays a list of products with options to filter by category, search by keyword, and sort by price.
- **Product Details**: Clicking on a product displays detailed information including the title, image, price, description, category, and rating.

### Filtering and Sorting

- **Filter by Category**: Use the dropdown menu to filter products by selected category.
- **Search**: Enter a keyword in the search box to find specific products.
- **Sort by Price**: Choose to sort products in ascending or descending order by price.

### Handling Product Details

- **View Details**: Click on a product to navigate to its detailed view, which includes comprehensive information and the option to go back to the home page.

## Acknowledgments

- **Fake Store API**: For providing the mock data used in this project.
- **Tailwind CSS**: For the utility-first approach to styling.
