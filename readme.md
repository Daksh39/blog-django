# Blogging Platform with Django

## Objective

Create a fully functional web application using Django to build a robust blogging platform.

## Requirements

1. **User Authentication and Authorization**
   - Implement JWT authentication system for secure user login and registration.

2. **Frontend Design**
   - Design a responsive frontend using HTML, CSS, and Bootstrap for a modern and user-friendly interface.

3. **CRUD Functionalities**
   - Develop Create, Read, Update, and Delete (CRUD) functionalities for blog posts.
   - Integrate rich text editing either through Django's admin interface or a custom frontend solution.

4. **Database Management**
   - Utilize PostgreSQL for efficient data storage and retrieval.

5. **Search Functionality**
   - Implement search functionality for blog posts.

6. **User Comments**
   - Include functionality for user comments on blog posts.

7. **Security**
   - Ensure secure handling of user data and password hashing.

## Additional Considerations

1. **Django Best Practices**
   - Apply best practices in Django development:
     - Use Django ORM for database interactions.
     - Implement class-based views where appropriate.
     - Utilize template inheritance for code reuse and organization.

2. **Version Control**
   - Use Git for version control.
   - Maintain a clear commit history to track changes and manage project evolution.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <repository-directory>

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt

3. **Set Up the Database**
    -Ensure PostgreSQL is installed and running.
    -Update database settings in settings.py.
    -Run migrations:
     ```bash
     python manage.py migrate

4. **Create a Superuser**
    '''bash
    python manage.py createsuperuser

5. **Run the Development Server**
    ```bash
    python manage.py runserver