# Recipe App API

A RESTful API for a recipe management application built with Python, Django REST Framework, and Docker. This project allows users to manage recipes, ingredients, and tags, complete with user authentication and image uploads.

---

## ✨ Key Features

* **User Authentication:** Secure user creation and token-based authentication (JWT).
* **Recipe Management:** Full CRUD (Create, Read, Update, Delete) functionality for recipes.
* **Ingredient & Tag System:** Create and assign ingredients and tags to recipes for easy filtering and organization.
* **Image Uploads:** Attach images to recipes to provide a rich user experience.
* **API Documentation:** Interactive API documentation powered by Swagger UI.

---

## 🛠️ Tech Stack

* **Backend:** Python, Django REST Framework
* **Database:** PostgreSQL
* **Containerization:** Docker, Docker Compose
* **API Testing & Docs:** Swagger UI

---

## 🚀 Getting Started

### Prerequisites

* Docker and Docker Compose must be installed on your local machine.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [YOUR_REPOSITORY_URL]
    cd [your-repository-folder]
    ```

2.  **Run the application with Docker Compose:**
    ```bash
    docker-compose up
    ```

3.  **Access the API Documentation:**
    * Navigate to `http://127.0.0.1:8000/api/docs/` in your web browser.

### Using the API

Once the application is running, you can use the interactive Swagger UI to test the endpoints:

1.  **Create a User:** Navigate to `POST /api/user/create/`, enter your details, and execute.
2.  **Retrieve an Auth Token:** Go to `POST /api/user/token/`, enter your new user credentials to receive an authentication token.
3.  **Authorize Your Session:**
    * Click the **Authorize** button at the top of the page.
    * In the `tokenAuth` field, enter `Token YOUR_TOKEN_HERE` (making sure to include the word "Token" and a space before the token).
    * Click **Authorize**.

You are now authenticated and can explore all the API's features!
