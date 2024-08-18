# Note Taker

## Description
This project aims to create an application - Note Taker that can be used to write and save notes. The application coorperates front-end and back-end (Express.js) developments to allow user to create, save & delete notes and able to save all note data to JSON file.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#apiroutes)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

1. Clone the repository to your local machine.
2. Run `npm install` to install the necessary dependencies (express& uuid).

## Usage

Local env:
1. Start application with command `npm start`.
2. Open browser and navigate to http://localhost:3001

Live env: 
1. Hitting the live link: https://module11challenge-notetaker.onrender.com 

## API Routes

- GET /api/notes: Retrieves all saved notes from the JSON file.
- POST /api/notes: Saves a new note to the JSON file. Each note is stored on a new line in the file.
- DELETE /api/notes/:id: Deletes a note with the specified ID from the JSON file.

## License
This project is licensed under MIT.

## Contributing
Happy to have your contribution! Simply fork the repo and submit a pull request.

## Tests
Manual tests done for this application with below use cases: 
- On the notes page, you can view existing notes in the left-hand column.
- You can enter a new note title and text in the right-hand column.
- The "Save" button appears when there is text in both the title and note fields.
- The "Clear Form" button appears when there is text in any of the input fields.
- Click on a note in the left-hand column to view it in the right-hand column.
- Click the "New Note" button to start writing a new note.

## Questions
For questions, please contact me on GitHub at [wendyydxiao](https://github.com/wendyydxiao) or email me at wendyxiao1023@gmail.com.
