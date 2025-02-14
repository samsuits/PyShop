# PyShop

Welcome to **PyShop**, a simple beginner application built with Django that allows you to store and display products in a table format. This application features an easy-to-use interface for managing product information, including images.

## Features

- Add products with names and images.
- Display a list of products with their corresponding images on the `/products` page.

## Requirements

- Python 3.x
- Django 3.x or higher

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/pyshop.git
   cd pyshop
   ```

2. **Create a virtual environment:**

   It’s a good practice to use a virtual environment for your projects. Here’s how to create and activate one:

   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install the dependencies:**

   If you have a `requirements.txt` file, run:

   ```bash
   pip install -r requirements.txt
   ```

   If you don't have one, install Django manually:

   ```bash
   pip install django
   ```

4. **Run migrations:**

   The project uses an SQLite database by default. Apply the database migrations by running:

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional):**

   If you want to manage your products through the Django admin, create a superuser account:

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**

   Start the Django development server:

   ```bash
   python manage.py runserver
   ```

   Your application should be running at `http://127.0.0.1:8000/`.

## Usage

- **Viewing Products:**
  Navigate to `http://127.0.0.1:8000/products/` to see the list of products displayed.

- **Admin Interface:**
  You can add or manage products via the Django admin interface at `http://127.0.0.1:8000/admin/`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Django Documentation: [https://www.djangoproject.com/](https://www.djangoproject.com/)