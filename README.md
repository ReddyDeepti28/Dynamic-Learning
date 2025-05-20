# D Learning Test Generator

A modern web application for generating and taking computer science tests using AI.

## Features

- Beautiful, responsive homepage with navigation
- AI-powered test generation based on user requests
- Interactive test-taking interface
- Detailed progress dashboard
- AI-powered feedback system

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root and add your Gemini API key:
```
GEMINI_API_KEY=your_api_key_here
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Start the development server:
```bash
python manage.py runserver
```

## Project Structure

- `core/` - Main Django project settings
- `quiz/` - Quiz application
- `templates/` - HTML templates
- `static/` - Static files (CSS, JS, images) 