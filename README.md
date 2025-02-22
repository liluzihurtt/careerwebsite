# Career Matcher API

## Overview
The Career Matcher API is a Node.js application that matches user input skills with predefined career options. It provides a simple API endpoint to receive user skills and returns the best career match based on the input.

## Project Structure
```
career-matcher-api
├── src
│   ├── controllers
│   │   └── careerController.js
│   ├── routes
│   │   └── careerRoutes.js
│   ├── services
│   │   └── careerService.js
│   └── app.js
├── package.json
├── .gitignore
└── README.md
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd career-matcher-api
   ```

3. Install the dependencies:
   ```
   npm install
   ```

## Usage

1. Start the server:
   ```
   npm start
   ```

2. The API will be running on `http://localhost:3000`.

## API Endpoint

### POST /api/careers/match
- **Description**: Matches user skills with career options.
- **Request Body**:
  ```json
  {
    "skills": "skill1, skill2, skill3"
  }
  ```
- **Response**:
  ```json
  {
    "bestMatch": "Career Name"
  }
  ```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## License
This project is licensed under the MIT License.