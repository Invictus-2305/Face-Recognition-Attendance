# Face Recognition Attendance System

This project is a web-based application that uses facial recognition technology to mark attendance. It leverages Firebase for database and storage, and uses Flask as the web framework. The application allows users to register their faces and mark their attendance through facial recognition.

## Features

- **User Registration:** Allows users to register by capturing and uploading their facial image along with their registration number and name.
- **Attendance Marking:** Marks attendance by recognizing the user’s face from a live image capture.
- **Firebase Integration:** Utilizes Firebase Realtime Database and Storage for storing user data and facial encodings.

## Technologies Used

- **Flask:** A lightweight WSGI web application framework.
- **Firebase:** For Realtime Database and Storage.
- **face_recognition:** A library for facial recognition.
- **OpenCV:** For image processing.
- **NumPy:** For numerical operations.

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Invictus-2305/Face-Recognition-Attendance.git
   cd Face-Recognition-Attendance
   ```

2. **Create and activate a virtual environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set up Firebase:**
   - Download your Firebase project’s service account key JSON file.
   - Save it in the project directory as `key.json`.
   - Make sure your Firebase Realtime Database and Storage are set up correctly.

## Usage

1. **Run the Flask application:**
   ```sh
   python app.py
   ```

2. **Access the application:**
   Open your web browser and go to `http://127.0.0.1:5000`.

3. **Register a User:**
   - Navigate to the registration page.
   - Fill in the registration form with the required details and submit.

4. **Mark Attendance:**
   - Navigate to the attendance page.
   - Capture or upload an image for face recognition.
   - The system will recognize the face and mark attendance accordingly.

## File Structure

- `app.py`: The main Flask application file.
- `templates/`: Directory containing HTML templates.
- `static/`: Directory containing static files (CSS, JS, images).
- `requirements.txt`: List of Python dependencies.

## Contributing

Contributions are welcome! Please create a pull request or raise an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
