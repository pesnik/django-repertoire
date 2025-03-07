# Django Repertoire

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Last Commit](https://img.shields.io/github/last-commit/pesnik/django-repertoire)

**A curated collection of Django projects and experiments, showcasing the journey toward mastery with Django in the cutting-edge tech world of 2025.**

---

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Projects](#projects)
  - [Basics](#basics)
  - [Intermediate](#intermediate)
  - [Advanced](#advanced)
  - [Experiments](#experiments)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

---

## Introduction

Welcome to **Django Repertoire**! This repository is a personal showcase of Django projects, experiments, and learning materials, reflecting a journey toward mastering the Django framework. Drawing inspiration from the performing arts—where a "repertoire" represents a collection of mastered works—this repository captures the evolution from foundational concepts to advanced, innovative applications.

The `*-repertoire` naming pattern (e.g., `django-repertoire`) signifies a sophisticated, mastery-focused approach, moving beyond beginner tutorials to a curated set of skills and projects. Here, you’ll find implementations that cover core Django concepts alongside modern trends like AI integration, asynchronous programming, and serverless computing, keeping it relevant to 2025’s tech landscape.

---

## Repository Structure

The repository is organized into directories, each containing self-contained Django projects with their own documentation and dependencies:

```
django-repertoire/
├── basics/
│   ├── simple_blog/
│   ├── user_auth/
│   └── ...
├── intermediate/
│   ├── rest_api/
│   ├── custom_middleware/
│   ├── ai_chatbot/
│   └── ...
├── advanced/
│   ├── async_programming/
│   ├── microservices/
│   ├── serverless_computing/
│   ├── ml_integration/
│   └── ...
└── experiments/
    ├── latest_features/
    ├── realtime_channels/
    └── ...
```

Each project directory includes:
- **README.md**: Project-specific details, including purpose and setup instructions.
- **requirements.txt**: Project-specific dependencies.
- **manage.py**: Django management script for running the project.

Root-level files include `.gitignore`, `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `LICENSE`, and this `README.md`.

---

## Projects

Projects are categorized by skill level and purpose, emphasizing challenges that resonate with 2025’s tech trends.

### Basics
- **[Simple Blog Application](basics/simple_blog/)**: A basic blog to master Django models, views, and templates.
- **[User Authentication](basics/user_auth/)**: Registration, login, and password reset using Django’s built-in auth system.

### Intermediate
- **[REST API with Django REST Framework](intermediate/rest_api/)**: A RESTful API for a blog, featuring serialization and authentication.
- **[Custom Middleware and Decorators](intermediate/custom_middleware/)**: Custom logging middleware and permission decorators for enhanced functionality.
- **[AI Chatbot Integration](intermediate/ai_chatbot/)**: An AI chatbot (e.g., using ChatterBot) integrated into a Django app, reflecting AI’s growing role.

### Advanced
- **[Asynchronous Programming](advanced/async_programming/)**: Leverage Django’s async capabilities for efficient concurrent request handling.
- **[Microservices with Django](advanced/microservices/)**: Build scalable services using REST or message queues.
- **[Serverless Computing](advanced/serverless_computing/)**: Deploy a Django app on serverless platforms like AWS Lambda.
- **[Machine Learning Integration](advanced/ml_integration/)**: Serve ML models (e.g., sentiment analysis) via Django APIs.

### Experiments
- **[Latest Features in Django](experiments/latest_features/)**: Projects showcasing Django 5.x features to stay current.
- **[Real-time Applications with Django Channels](experiments/realtime_channels/)**: WebSocket-based chat or live update applications.

---

## Getting Started

To explore the projects, ensure you have the following installed:
- **Python 3.x**
- **pip** (Python package manager)
- **Git**

---

## How to Use

Follow these steps to set up and run any project:

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/pesnik/django-repertoire.git
   ```

2. **Navigate to a project directory**:  
   For example, the Simple Blog Application:  
   ```bash
   cd django-repertoire/basics/simple_blog
   ```

3. **Create and activate a virtual environment**:  
   - On Windows:  
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```
   - On macOS/Linux:  
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

4. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply migrations**:  
   ```bash
   python manage.py migrate
   ```

6. **Run the server**:  
   ```bash
   python manage.py runserver
   ```

> **Note**: Some projects may require additional setup (e.g., database configuration or third-party services). Check the project’s `README.md` for details.

---

## Contributing

Contributions are encouraged! To contribute:

1. Fork the repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature/your-feature
   ```  
3. Commit your changes:  
   ```bash
   git commit -m "Add your message"
   ```  
4. Push to your branch:  
   ```bash
   git push origin feature/your-feature
   ```  
5. Submit a pull request.

Please follow the [code of conduct](CODE_OF_CONDUCT.md) and [contributing guidelines](CONTRIBUTING.md).

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [Django Documentation](https://docs.djangoproject.com/)
- [Real Python](https://realpython.com/)
- [Django Girls Tutorial](https://tutorial.djangogirls.org/)

---

## Contact

Questions or feedback? Open an issue or contact [pesnik](https://github.com/pesnik).
