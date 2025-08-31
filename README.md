# Smart Recipe Generator

Suggests matching recipes from a local database based on ingredients you provide.

## Tech
- Node.js + Express (backend & static frontend)
- Local `recipes.json` (25 recipes)

## Setup
1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Environment**
   - Create a `.env` file in the project root:
     ```env
     PORT=3000
     ```

3. **Run the server**
   ```bash
   npm start
   ```
   Visit: http://localhost:3000

4. **Live Demo**
[Click here to view the hosted app](https://smart-reciepe-generator.onrender.com/)


5. **Approach**
The Smart Recipe Generator is a project that helps people find recipes using the ingredients they already have. The app is built with Node.js and Express, which handle both the backend logic and a simple frontend. A recipe database with 25 dishes was created, and each recipe has ingredients, steps, cooking time, and nutrition details. When the user enters ingredients, the system compares them with the database and gives the recipes that match the most. This is done using an “overlap score,” which means more common ingredients give a higher score. The app can also suggest replacement items when some ingredients are missing. Filters like vegetarian, gluten-free, and cooking difficulty make the results more useful.

The application is designed to be simple, fast, and easy to use. It shows loading states while searching and works well on both mobile and desktop screens. Users can see cooking instructions, nutrition information, and can also adjust serving sizes. Extra features like saving favorite recipes and rating them can be added in the future. The backend code is written in a clean and organized way so that more recipes and cuisines can be added later without problems. The app is hosted on Render, which makes it available online for everyone to test. In short, the project connects user inputs with recipe data, handles missing items, and still gives a smooth, helpful cooking experience.
