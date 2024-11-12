

# Contact Management App - Frontend

This is the Angular frontend for the Contact Management App, designed to manage contacts with functionalities like adding, editing, viewing, and deleting contacts.

## Features
- **Contact List**: View a list of all contacts.
- **Add/Edit Contact**: Add new contacts and edit existing ones.
- **Delete Contact**: Remove unwanted contacts.
- **Search and Filter**: Search contacts by name and filter by category.

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/My_contact_mangement_app.git
    cd My_contact_mangement_app/frontend
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Run the app**:
    ```bash
    ng serve
    ```

4. **Access the app**: Open [http://localhost:4200](http://localhost:4200) in your browser.

## File Structure

- **src/app/components**: Contains Angular components for the app, including the contact list, contact form, and related templates.
- **src/app/services/contact.service.ts**: Provides methods for HTTP requests to the .NET API backend.
- **src/app/models/contact.model.ts**: Defines the structure for contact data.

## Configuration

- Ensure API endpoints in `contact.service.ts` match the backend URLs.
- Confirm CORS settings in the .NET backend if running frontend and backend on different ports.

## Requirements
- Angular CLI v12 or later
- Node.js v14 or later

## Troubleshooting

- **CORS Issues**: Check .NET API for CORS policy setup.
- **API Errors**: Verify backend is running and URLs in `contact.service.ts` are correct.

