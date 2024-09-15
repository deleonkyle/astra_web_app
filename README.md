---

# Astra Web App

The **Astra Web App** is a web-based application designed to manage and track various operations efficiently. 
Built using modern web development technologies, this app offers a user-friendly interface and robust backend functionality for managing data seamlessly.

## Features

- **User Management**: Create, read, update, and delete user profiles.
- **Data Visualization**: Visualize data using charts and graphs.
- **Task Tracking**: Keep track of tasks with due dates, priorities, and statuses.
- **Search and Filter**: Advanced search and filter options to easily locate data.
- **Responsive Design**: Fully responsive design for a seamless experience across devices.

## Tech Stack

- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Backend**: Python Flask
- **Database**: SQLite
- **Hosting**: Render.com

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/deleonkyle/astra_web_app.git
   cd astra_web_app
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database:
   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```

4. Run the application:
   ```bash
   flask run
   ```

5. Access the web app at `http://localhost:5000`.

## Usage

Once the app is running, you can:

- Register a new user or log in with existing credentials.
- Add, view, and update data records.
- Use the task tracker to manage and complete tasks.
- Visualize data trends and summaries with built-in charts.

## Project Structure

```bash
astra_web_app/
│
├── static/              # Static files (CSS, JavaScript, images)
├── templates/           # HTML templates
├── app.py               # Main Flask app
├── models.py            # Database models
├── forms.py             # Flask-WTF forms
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
