# CI/CD Final Project

This project demonstrates a complete CI/CD pipeline using GitHub Actions and Tekton on OpenShift.

## Project Structure

- `app.py`: Flask application
- `test_app.py`: Test suite
- `requirements.txt`: Python dependencies
- `.github/workflows/workflow.yml`: GitHub Actions workflow
- `.tekton/tasks.yml`: Tekton tasks

## Setup Instructions

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python app.py`
4. Run tests: `pytest`

## CI/CD Pipeline

The project uses:
- GitHub Actions for linting and testing
- Tekton for OpenShift pipeline tasks
- OpenShift for deployment

## Screenshots

Please refer to the following screenshots in the project documentation:
- OpenShift PVC details
- GitHub Actions running successfully
- OpenShift Pipeline details
- OpenShift Pipeline running successfully
- Application logs from OpenShift console