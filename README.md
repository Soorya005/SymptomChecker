# Symptom Checker & Medical Assistant

## Overview
The *Symptom Checker* is a web application that allows users to input their symptoms and receive a list of potential diseases. It helps individuals identify possible health conditions based on their symptoms and provides valuable insights to assist them in making informed health decisions. The system uses data-driven predictions to generate probable outcomes based on input symptoms.

## Features
- User-friendly interface to input symptoms and the number of days experienced.
- Generates a list of possible diseases based on user input.
- API-driven for accurate and real-time results.
  
## Technologies Used
- *Frontend*: React, Vite
- *Backend*: Node.js, Express
- *APIs*: Integrated APIs to fetch disease data

## Installation

### Prerequisites
- Node.js installed on your system
- MongoDB (if applicable)
  
### Steps
1. Clone the repository:
    bash
    git clone https://github.com/Noel9907/Rag_Hack
    
2. Navigate to the project directory:
    bash
    cd symptom-checker
    
3. Install dependencies:
    bash
    npm install
    
4. Start the server:
    bash
    npm run dev
    

## Usage
1. Open the app in your browser.
2. Enter your symptoms and the duration.
3. The app will display possible diseases based on your input.

## API Endpoints
- *POST* /api/input/save: Saves user input (symptoms and days).
- *GET* /api/input/diseases?symptoms=symptom1,symptom2: Fetches probable diseases based on symptoms.

## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request. We welcome contributions that can improve the user experience and overall functionality of the app.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
