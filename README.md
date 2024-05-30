# Instagram Clone

This project is a clone of Instagram built using Python, Django, HTML, CSS, and JavaScript. It includes features such as user authentication, profile management, post uploads, feeds, follow/unfollow functionality, and like/unlike posts.

## Features

- **User Authentication**: Sign up and sign in functionalities.
- **Profile Management**: Users can create and edit their profiles.
- **Post Uploads**: Users can upload photos to their profiles.
- **Feeds**: Users can see posts from people they follow.
- **Follow/Unfollow**: Users can follow and unfollow other users.
- **Like/Unlike Posts**: Users can like or unlike posts.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment:**

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```bash
        source venv/bin/activate
        ```

4. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Run migrations:**

    ```bash
    python manage.py migrate
    ```

6. **Create a superuser:**

    ```bash
    python manage.py createsuperuser
    ```

7. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

8. **Open your browser and visit:**

    ```plaintext
    http://127.0.0.1:8000/
    ```

## Usage

1. **Sign up or log in to create a profile.**
2. **Upload posts by clicking on the upload button.**
3. **View feeds to see posts from users you follow.**
4. **Follow or unfollow users to manage your feed.**
5. **Like or unlike posts.**

## Technologies Used

- **Backend**: Python, Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default, can be changed)

## Contributing

1. **Fork the repository.**
2. **Create a new branch:**

    ```bash
    git checkout -b feature-branch
    ```

3. **Make your changes and commit them:**

    ```bash
    git commit -m 'Add new feature'
    ```

4. **Push to the branch:**

    ```bash
    git push origin feature-branch
    ```

5. **Submit a pull request.**

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, feel free to reach out to me at [your-email@example.com].

---

Happy coding!
