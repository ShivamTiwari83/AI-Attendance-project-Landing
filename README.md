# AI Attendance Project App

A desktop attendance application built with Python that supports face and voice recognition attendance tracking. The project includes a GUI for teachers and students, subject management, enrollment workflows, and offline database storage.

## Features

- Face recognition based attendance
- Voice recognition based attendance
- Subject creation and enrollment
- Attendance result viewing
- Student and teacher screens with dialogs for actions
- Local database storage using SQLite

## Project Structure

- `app.py` - Main application entry point
- `requirements.txt` - Python dependencies
- `src/components/` - UI dialog components and reusable widgets
- `src/database/` - Database configuration and helper modules
- `src/pipelines/` - Face and voice processing pipelines
- `src/screens/` - Main GUI screens for students and teachers
- `src/ui/` - Layout and base UI configuration

## Setup

1. Create and activate a Python virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

## Usage

- Launch `app.py` to open the application.
- Use the teacher screen to create subjects and enroll students.
- Use face or voice attendance dialogs to record attendance.
- View attendance results in the provided dialogs.

## Notes

- Ensure your camera and microphone permissions are enabled for face and voice attendance.
- The app stores data locally; back up the database if needed.

## License

This project is provided as-is. Customize it for your own attendance automation workflow.