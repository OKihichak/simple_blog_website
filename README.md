
![сімпл1](https://github.com/user-attachments/assets/c6c146a9-43d9-4d7f-8f18-686024c63cbe)
![сімпл2](https://github.com/user-attachments/assets/723f509c-34df-4a09-ba8c-bcc71b3cefe8)
![сімпл3](https://github.com/user-attachments/assets/4e0472b9-5162-47c5-aff7-518deb7a65cd)
![сімпл4](https://github.com/user-attachments/assets/f8583529-bc52-4eb0-91a0-577693d6e088)


# 📝 Django Blog Application

📝 **Contents**
- [Introduction](#-introduction)
- [Technology Stack](#-technology-stack)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [How to Run](#-how-to-run)
- [Contribution Guidelines](#-contribution-guidelines)
- [Get in Touch](#-get-in-touch)

## 🌟 Introduction
The **Django Blog Application** is a web platform that enables users to create, manage, and publish blog posts. With full support for user authentication, comment moderation, and CRUD operations, this application is built to be both scalable and user-friendly.

## 💻 Technology Stack
- **Django**: The main web framework used for building the application.
- **Bootstrap 3**: For responsive design and styling.
- **SQLite**: Default database for local development.
- **HTML/CSS/JavaScript**: For the frontend interface.

## ✨ Features
- **User Authentication**: Login, logout, and session management.
- **Blog Posts**: Create, edit, publish, and delete blog posts.
- **Commenting System**: Add, approve, and delete comments on posts.
- **Draft Management**: Save posts as drafts and publish them later.
- **Responsive Design**: Fully responsive UI for all devices.

## 🗂️ Project Structure
- **`blog/`**: Contains the core blog functionality.
  - **`models.py`**: Defines `Post` and `Comment` models.
  - **`views.py`**: Handles displaying, creating, editing, and deleting posts and comments.
  - **`forms.py`**: Includes forms for creating posts and adding comments.
  - **`urls.py`**: Maps URLs to their respective views.
  - **`admin.py`**: For managing models via the Django admin interface.
  
- **`templates/blog/`**: Contains HTML templates.
  - **`base.html`**: Base template extended by other templates.
  - **`post_list.html`**: Displays a list of published posts.
  - **`post_detail.html`**: Shows details of a single post with comments.
  - **`post_form.html`**: Used for creating and editing posts.
  - **`comment_form.html`**: Form for adding comments.
  - **`login.html`**: User login page.
  
- **`static/`**: Stores static files like CSS and JavaScript.
  - **`css/blog.css`**: Custom styles for the blog.

- **`manage.py`**: Django’s command-line utility for administrative tasks.

## 🚀 How to Run
1. **Clone the repository:**
    ```bash
    git clone https://github.com/OKihichak/simple_blog_website.git
    cd django-blog-app
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # For Windows use venv\Scripts\activate
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply the migrations to set up the database:**
    ```bash
    python manage.py migrate
    ```

5. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

6. **Access the application:** Open your web browser and navigate to `http://localhost:8000`.

## 🤝 Contribution Guidelines
Interested in contributing? Here’s how you can get started:

1. **Fork the repository.**
2. **Create a new branch:**
    ```bash
    git checkout -b feature/YourFeatureName
    ```
3. **Make your changes and commit them:**
    ```bash
    git commit -m 'Add YourFeatureName'
    ```
4. **Push to the branch:**
    ```bash
    git push origin feature/YourFeatureName
    ```
5. **Open a pull request** to discuss and merge your changes.

## 📧 Get in Touch
- **Email**: oleg15062005@gmail.com
- **GitHub**: [Oleh Kihichak](https://github.com/OKihichak)

