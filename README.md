
# Gold Thread System

## Overview

This project is a **Gold Thread System** with both desktop and web interfaces. It manages various operations related to gold threads, including client management, inventory tracking, order processing, and financial reporting. The system is bilingual, supporting both English and Arabic.

### Key Files:
- **main.py** - Desktop GUI application using Tkinter
- **app.py** - Web application using Flask
- **database.py** - Database operations and schema
- **models.py** - Data models
- **utils.py** - Utility functions
- **web_app.py** - Additional web routes
- **app_init.py** - Flask app initialization

### Key Features:
- **Client Management**
- **Inventory Tracking**
- **Order Processing**
- **Payment Handling**
- **Financial Reporting**
- **Bilingual Support (EN/AR)**

## Database Schema:
The system uses an SQLite database (`gold_thread.db`) with the following tables:
- **Users** (authentication)
- **Clients**
- **Workers**
- **Manufacturers**
- **Orders**
- **Order Items**
- **Payments**

## Application Structure:
The codebase is structured to separate concerns between data, UI, and business logic:
- **Database and Models:** `database.py`, `models.py`
- **Desktop UI:** `main.py`
- **Web Interface:** `app.py`, `web_app.py`
- **Flask App Initialization:** `app_init.py`

## How to Run the Application:

### Desktop Version:
Run the desktop version using the following command:
```bash
python main.py
```

### Web Version:
Run the web version (Flask app) by starting the server:
```bash
python app.py
```
The web application will be accessible at [http://localhost:5000](http://localhost:5000).

## Default Login:
- **Username:** admin
- **Password:** admin

## Workflows:
- **"Gold Thread App"** - Runs the desktop version of the application.
- **"Gold Thread Web App"** - Runs the web version of the application on port 5000.

## Development Notes:
If you need to continue the development of this project, the following files are the most important:
- **`database.py`** - Contains the database structure and operations.
- **`models.py`** - Contains the data models.
- **`main.py`** - Contains the desktop GUI.
- **`app.py`** - Contains the web interface.

## Technologies Used:
- **Backend:** Flask
- **Frontend:** Bootstrap (for web)
- **Desktop UI:** Tkinter
- **Database:** SQLite
- **Multi-language Support:** Locale Data (English/Arabic)
