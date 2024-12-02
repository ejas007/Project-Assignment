# All Records Project

## Project Overview

The *All Records* project is a simple web application for managing a list of items. It allows users to view item details in a table format and perform CRUD operations. If no items are present, an appropriate message is displayed. The application uses *Django* for server-side logic and dynamic content rendering.

---

## Features
- **View Items**: Display a list of items with details.
- **Add New Items**: Create new item entries.
- **Update Items**: Edit existing items.
- **Delete Items**: Remove items from the list.
- **Data Validation**: Ensure valid inputs, such as preventing future dates.

---

## Technologies Used
- **Django**: High-level Python web framework.
- **SQLite**: Lightweight database for data storage.

---

## Prerequisites
Before starting, ensure you have:
- **Python** installed (version 3.8+ recommended).
- **Django** installed (`pip install django`).
- Basic understanding of **HTML**, **CSS**, and **Django**.

---

## Installation and Setup

### 1. Clone the Repository
```bash
git clone <repository-url>
cd Project1

SetUp the DataBase
```bash
python manage.py makemigrations
python manage.py migrate


## Run the Development Server
```bash
python manage.py runserver