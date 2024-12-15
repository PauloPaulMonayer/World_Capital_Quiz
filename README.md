# World Capital Quiz

## Introduction
The **World Capital Quiz** is an interactive application designed to test your knowledge of world capitals. This project is built with a Node.js backend and utilizes static resources for the frontend.

## Features
- Interactive quiz format to guess world capitals.
- Uses a CSV file (`capitals.csv`) to store the data of countries and their capitals.
- A user-friendly interface for engaging gameplay.
- Backend logic implemented in Node.js for dynamic quiz generation.

## Technologies Used
- **Node.js**: Backend server.
- **Express.js**: Web framework for routing and server-side functionality.
- **CSV Parsing**: Data source for countries and capitals.
- **HTML, CSS, JavaScript**: Frontend technologies for the user interface.

## Installation

### Prerequisites
- Ensure you have Node.js installed on your machine.

### Steps
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd World_Capital_Quiz
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the application:
   ```bash
   node index.js
   ```
5. Open your browser and navigate to `http://localhost:3000` to access the quiz.

## Project Structure
```
World_Capital_Quiz/
├── capitals.csv           # Data source of countries and capitals
├── index.js               # Main server file
├── node_modules/          # Installed dependencies
├── package.json           # Project metadata and dependencies
├── package-lock.json      # Dependency tree lock file
├── public/                # Static assets (CSS, JS, images)
├── solution.js            # Solution logic
├── views/                 # HTML templates (if using templating engine)
```

## Usage
1. Launch the application using the steps above.
2. Follow the instructions on the interface to start the quiz.
3. Submit your answers and get instant feedback on your knowledge of world capitals.

## Future Enhancements
- Add more detailed statistics for user performance.
- Implement a database to store user scores and progress.
- Enable multi-language support for a broader audience.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---
Feel free to contribute by submitting issues or pull requests to improve this project!
