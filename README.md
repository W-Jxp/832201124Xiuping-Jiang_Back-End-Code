---

### Backend (`README.md`)

```markdown
# Contacts Management - Backend

## Project Overview
This is the backend API for a contact management application, developed with Flask. The API enables CRUD operations on contact data and allows the frontend to add, view, update, and delete contact information stored on the server.

## Folder Structure
README.md
scr code.py
codestyle.md

## Features
Add Contact: Receive new contact data via a POST request and store it in the server.
View Contacts: Respond to GET requests to return all saved contacts.
Edit Contact: Update contact details based on the contact's unique ID.
Delete Contact: Remove a contact using its unique ID.

## Installation
1. Clone the repository:
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
The backend code adheres to PEP 8 and includes standards specific to Flask as described in codestyle.md.

Deployment
To deploy this backend on a cloud server, ensure you have Flask and Gunicorn (or another WSGI server) configured.
