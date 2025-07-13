# flask-to_do-simple-app
A simple, secure Flask-based To-Do web application. Users can register, log in, and manage their personal tasks with a clean dashboard interface. All user data and tasks are stored in a local SQLite database, and passwords are securely hashed using bcrypt.

## Features

- User registration and login
- Password hashing for security
- Add, edit, and delete tasks
- Responsive Bootstrap UI
- Session-based authentication

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/To_do-no-1.git
   cd To_do-no-1
   ```

2. **Install dependencies:**
   ```sh
   pip install flask flask_sqlalchemy bcrypt
   ```

3. **Run the app:**
   ```sh
   python app.py
   ```

4. **Access the app:**
   Open [http://localhost:5000](http://localhost:5000) in your browser.

## Project Structure

- `app.py` — Main Flask application
- `templates/` — HTML templates for UI
- `instance/datausers.db` — SQLite database

## License

MIT License

---

Crafted with ❤️ using Flask & Bootstrap.
