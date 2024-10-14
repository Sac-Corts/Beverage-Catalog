# 🍹 Beverage Catalog
This project is a simple beverage catalog application that allows users to explore different drinks using the TheCocktailDB API. The app provides users with the ability to search for drinks by categories, view details, and manage a list of favorite drinks. It's built using modern web technologies to ensure performance, responsiveness, and a great user experience.

## :star2: Features
- **Home and Favorites Pages:** View a variety of drinks on the home page and access a personalized list of favorite drinks.
- **Search by Categories:** Easily search for drinks by selecting different categories.
- **Add to/Remove from Favorites:** Seamlessly add or remove drinks from your list of favorites.
- **Drink Details:** View detailed information about each drink, including ingredients, instructions, and an image.
- **Notifications:** Receive notifications when a drink is added to or removed from your favorites list.

## :pushpin: Technologies Used
- **React (with TypeScript)** for building a robust, maintainable user interface.
- **Vite** for fast development and optimized production builds.
- **Tailwind CSS** for flexible and efficient styling with utility-first CSS.

## :ok_hand: Performance Optimization

To optimize performance and ensure clean, maintainable code, the following tools were used:

- **React Router:** React Router is used for client-side routing, which allows seamless navigation between the home and favorites pages without reloading the page. This enhances the user experience and speeds up page transitions.
- **Zustand:** Zustand is a minimalistic state management library that was used to efficiently manage the application's state, such as handling favorite drinks and ensuring fast and reactive UI updates with minimal boilerplate.
- **Zod and Axios:** Zod is used for schema validation to ensure API responses match expected data structures, improving error handling and maintaining data integrity. Axios is utilized for making HTTP requests to TheCocktailDB API, ensuring efficient data fetching with promise-based syntax.
- **Heroicons/React:** Heroicons are used to provide high-quality SVG icons, enhancing the user interface's visual appeal, and ensuring scalability and flexibility in design.
- **HeadlessUI/React:** Headless UI provides unstyled, fully accessible UI components, making it easier to build complex interactive elements like modals, while maintaining full control over the styling.

## :globe_with_meridians: Site
**Site:** https://beverage-catalog-sac.netlify.app/

## 🚀 Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/Beverage-Catalog.git
```
### 2. Navigate to the project folder
```bash
cd Beverage-Catalog
```
### 3. Install dependencies
```bash
npm install
```
### 4. Start the application
```bash
npm run dev
```
### 5. Build the application
```bash
npm run build
```