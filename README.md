# Phone Management System Readme

This Node.js application serves as a simple phone management system allowing users to add contacts, dial phone numbers, view contact lists, and check call logs. Below is an overview of the key features and functionalities.

## Features

1. **Contact Management**
   - Add new contacts with a name and phone number.
   - Remove existing contacts.
   - Edit contact information.

2. **Phone Dialing**
   - Dial phone numbers from the contacts list.
   - Displays call history.

3. **Observer Pattern**
   - Utilizes the observer pattern to notify observers when a phone call is initiated.

## JSON Files

- Contacts and call history data are stored in separate JSON files (`contacts.json` and `call_history.json`).
- Data is loaded from and saved to these files, ensuring persistent storage between sessions.

## Usage

1. **Add a Contact**
   - Choose option (1) in the main menu.
   - Enter the contact name and phone number when prompted.

2. **Dial a Phone Number**
   - Choose option (2) in the main menu.
   - Enter the phone number to initiate a call.

3. **View Contacts**
   - Choose option (3) in the main menu to view the list of contacts.

4. **View Call Logs**
   - Choose option (4) in the main menu to display the call history.

## Observers

The application includes two observers:
- `Observer1`: Prints the phone number being dialed.
- `Observer2`: Prints the last 10 digits of the phone number being dialed.

## Running the Application

1. Install Node.js and npm.
2. Clone the repository.
3. Navigate to the project directory and run `npm install`.
4. Execute `node filename.js` in the terminal to launch the application.
