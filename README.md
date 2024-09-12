# Note Manager

Welcome to **Note Manager**, a simple yet powerful note-taking application that lets you easily organize your thoughts and tasks. This app uses **Express.js** to power the backend and **JSON** to store your notes.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Screenshots](#screenshots)
- [Deployed Application](#deployed-application)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Contact](#contact)

## Description
As a small business owner, staying organized is crucial. That's where **Note Manager** comes in. This application allows you to easily write, save, and access your notes whenever you need them. With a clean and intuitive interface, managing your tasks has never been simpler.

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/mayenawardak/note-manager.git
    ```
   
2. Navigate into the project directory:
    ```bash
    cd note-manager
    ```
   
3. Install the necessary dependencies:
    ```bash
    npm install
    ```

4. Run the app:
    ```bash
    node server.js
    ```

5. Visit `http://localhost:3001` in your browser to start managing your notes.

## Usage
- **Home Page:** Presents a simple landing page where you can access your notes.
- **Notes Page:** Here, you can view existing notes, add new ones, and manage your to-do list effortlessly.
- **Save & Delete:** Notes are stored using the JSON format, making it easy to update, save, and even delete them if necessary.

### API Endpoints
- **GET** `/api/notes` - Retrieves all saved notes.
- **POST** `/api/notes` - Adds a new note.
- **DELETE** `/api/notes/:id` - Deletes a note by ID.

## Screenshots

### Home Page
![Home Page](./assets/images/homepage.png)

### Notes Page
![Notes Page](./assets/images/notespage.png)

## Deployed Application
The app is live! You can check it out [here](https://your-render-deployed-app-url).

## Technologies Used
- **Express.js**
- **Node.js**
- **UUID** for unique note IDs
- **HTML/CSS** for the front end
- **JavaScript** for back end and API

## License
This project is licensed under the MIT License.

## Contact
For any questions, feel free to reach out to me at:
- Email: mayenawardak03@icloud.com
- GitHub: [mayenawardak](https://github.com/mayenawardak)