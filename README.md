# Contacts Management - Backend

## Project Overview
This backend API, developed with Flask, provides CRUD operations for managing contact information. It allows the frontend to add, view, update, and delete contacts stored on the server.

## Folder Structure
. ├── README.md ├── src │ └── code.py ├── codestyle.md

## Features
- **Add Contact**: Stores new contact data received via a POST request.
- **View Contacts**: Responds to GET requests to retrieve all saved contacts.
- **Edit Contact**: Updates details of a specific contact using the contact's unique ID.
- **Delete Contact**: Removes a contact by its unique ID.

## Installation
1. **Clone the repository**:
   ```bash
   git clone <repository_url>
Navigate to the project folder:
cd C:\Users\Administrator>python 后端代码（终）.txt
Install dependencies:
pip install -r requirements.txt
Run the server:
python main.py
API Endpoints
POST /contacts: Adds a new contact.
GET /contacts: Retrieves all contacts.
PUT /contacts/{id}: Updates a contact by ID.
DELETE /contacts/{id}: Deletes a contact by ID.
Code Standards
The backend code follows PEP 8 guidelines and uses Flask-specific standards as described in codestyle.md.

Deployment
To deploy this backend on a cloud server, ensure that Flask and a WSGI server such as Gunicorn are configured.
