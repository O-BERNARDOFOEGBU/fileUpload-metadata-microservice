# File Metadata Microservice

This project is a File Metadata Microservice that allows users to upload a file and receive metadata about the uploaded file, including its name, type, and size.

## Live Demo

You can see a live demo of the project here: [File Metadata Microservice](http://localhost:3000/)

## Table of Contents

- [File Metadata Microservice](#file-metadata-microservice)
  - [Live Demo](#live-demo)
  - [Table of Contents](#table-of-contents)
  - [Project Structure](#project-structure)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)
  - [Usage](#usage)
  - [API](#api)
  - [License](#license)

## Project Structure

```plaintext
project/
│
├── public/
│   └── style.css
├── views/
│   └── index.html
├── .env
├── package.json
└── server.js
```

## Features

Upload a file through a form
Receive file metadata (name, type, size) in the response

## Technologies Used

Node.js
Express.js
Multer
dotenv
Cors

## Installation

Clone the repository:

```plaintext
git clone https://github.com/O-BERNARDOFOEGBU/URL-exercise-tracker-microservice.git
```

Navigate to the project directory:

cd URL-exercise-tracker-microservice

Install dependencies:

npm install

## Usage

Create a .env file in the root directory and add the following content:

```plaintext
Copy code
PORT=3000
Start the server:
```

npm start
Open your browser and go to http://localhost:3000/ to access the File Metadata Microservice.

## API

POST /api/fileanalyse
Upload a file and receive its metadata.

Request
Content-Type: multipart/form-data
Form Data:
upfile (file): The file to be uploaded
Response

```json
{
  "name": "filename.ext",
  "type": "file/type",
  "size": 12345
}
```

## License

This project is licensed under the MIT License.
