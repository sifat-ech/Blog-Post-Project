# Blog Post Project

A full-stack blog application built with Django, HTML, and CSS, where users can sign up, log in, and post content. Users can comment on posts, but only the post creator can edit or delete their own posts.

## Features

- **User Authentication**: Sign up, log in, and reset passwords via email verification.
- **Post Creation**: Users can create blog posts with a title and description.
- **Public Visibility**: All posts are visible to everyone.
- **Comment System**: Anyone can comment on posts.
- **Post Management**: Only the author can edit or delete their own posts.

## Tech Stack

- **Backend**: Python Django
- **Frontend**: HTML, CSS
- **Database**: SQLite

## Installation & Setup

1. **Clone the Repository**
   ```sh
   git clone https://github.com/sifat-ech/Blog-Post-Project.git
   cd Blog-Post-Project
   ```

2. **Create a Virtual Environment & Activate it**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Apply Migrations**
   ```sh
   python manage.py migrate
   ```

5. **Create a Superuser (Optional, for Admin Panel)**
   ```sh
   python manage.py createsuperuser
   ```

6. **Run the Development Server**
   ```sh
   python manage.py runserver
   ```

7. **Access the Application**
   - Open your browser and go to: `http://127.0.0.1:8000/`

## Usage

- **Sign Up/Login**: Create an account or log in.
- **Forgot Password**: Enter your email to receive a reset code.
- **Create Post**: Add a title and description, then publish it.
- **View Posts**: All posts are visible on the homepage.
- **Comment**: Anyone can comment on posts.
- **Edit/Delete**: Only the post creator can edit or delete their post.

## Contributing

Feel free to contribute by submitting pull requests. Make sure to follow best coding practices and provide clear commit messages.

