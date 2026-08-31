# AI Attendance Management System

An AI-based attendance management system developed to make student attendance easier to record and manage. The project combines facial recognition and voice verification to identify students before marking their attendance.

The system includes separate interfaces for students and teachers. The student side focuses on the attendance and verification process, while the teacher side provides features for managing and viewing attendance.

## Key Features

- Student identification using facial recognition
- Voice-based verification
- Attendance marking after successful verification
- Separate student and teacher interfaces
- Attendance management for teachers
- Web-based landing page for the application

## Technologies

**Backend / Application**
- Python
- Streamlit
- Flask

**AI / Computer Vision**
- OpenCV
- Facial Recognition

**Frontend**
- HTML
- CSS
- JavaScript

## Project Structure

The repository contains two parts of the project:

### `ai-attendance-project-app-main`

Contains the main attendance application, including the student and teacher screens and the verification-related functionality.

### `ai-attendance-project-landing-main`

Contains the landing page of the project along with its HTML templates, static files and deployment configuration.

## Application Flow

1. The student opens the attendance application.
2. The student goes through the required identity verification.
3. Facial recognition and voice verification are used as part of the verification process.
4. Once the student is verified, attendance can be marked.
5. Teachers can access the teacher interface to manage and view attendance information.

## Running the Project

Clone the repository:

```bash
git clone https://github.com/Mridul7204/ai-attendance-system.git
