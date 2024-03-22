# Learning Logs

Learning Logs is a web application built with Django, designed to help users keep track of their learning topics and progress. With Learning Logs, users can create topics they want to learn about and make entries to record their thoughts, progress, or any new insights they've gained in their learning journey.

## Features

- **User Authentication**: Secure user authentication system allowing users to sign up, log in, and manage their accounts.
- **Topics Management**: Create, view, update, and delete topics you want to learn about.
- **Entries Creation**: Add entries to your topics, recording your thoughts, progress, or any new learnings.
- **Topic-specific Entries**: Entries are organized by topics, making it easy to manage and review your progress on each topic.
- **Search Functionality**: Search feature allowing users to find topics or entries quickly.

## Installation

1. Clone the repository:

    ```bash
    git clone <repository_url>
    ```

2. Navigate to the project directory:

    ```bash
    cd learning_logs
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

5. Run the development server:

    ```bash
    python manage.py runserver
    ```

6. Access the application at `http://localhost:8000` in your web browser.

## Usage

1. Create an account or log in if you already have one.
2. Once logged in, you'll be redirected to the dashboard where you can start managing your topics and entries.
3. To create a new topic, click on the "New Topic" button and fill in the details.
4. After creating a topic, you can add entries to it by clicking on the topic name and then the "Add new entry" button.
5. Fill in the entry form with your thoughts or progress, and save it.
6. You can view, edit, or delete topics and entries using the provided options.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for any features or improvements you'd like to see.

## License

This project is licensed under the [MIT License](LICENSE).

---
