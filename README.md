# CookConnect Documentation

### Overview
CookConnect is a web application designed for food enthusiasts to discover, share, and manage their favorite recipes. The platform features a user-friendly interface built with React.js and a robust backend powered by Django. It is deployed on AWS for scalability and reliability.

### Tech Stack
- **Frontend:** React.js, HTML, CSS, Material-UI
- **Backend:** Django, Django REST Framework
- **Database:** PostgreSQL
- **Deployment:** AWS S3, AWS EC2, AWS CloudFront, Custom VPC

### Features
1. **Recipe List:** View a list of all recipes with basic information.
2. **Recipe Detail:** Detailed view of selected recipes, including ingredients, steps, and user comments.
3. **Add Recipe:** Form to add new recipes with title, ingredients, steps, category, and photo upload.
4. **Recipe Search:** Search for recipes by name, category, or ingredients.

### API Endpoints
- **GET /recipe:** Fetch all recipes.
- **POST /recipe:** Add a new recipe.
- **GET /recipe/{id}:** Fetch details of a specific recipe.
- **PUT /recipe/{id}:** Update a specific recipe.
- **DELETE /recipe/{id}:** Delete a specific recipe.

