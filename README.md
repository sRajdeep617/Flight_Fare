# Flight Fare Prediction

## Project Overview
The Flight Fare Prediction project aims to predict the fare of flights based on various input parameters. This project includes a web application built using Flask and a mobile application that interacts with the web app to get flight fare predictions.

## Features
- **Web Application**: A user-friendly web interface to input flight details and get fare predictions.
- **Mobile Application**: A mobile app that communicates with the web app to fetch flight fare predictions.
- **API Endpoints**:
    - `/predict_mobile`: Endpoint for the mobile app to get flight fare predictions.
    - `/predict`: Endpoint for the web app to get flight fare predictions.

## Technologies Used
- **Flask**: A micro web framework used to build the web application.
- **Render**: A cloud platform used to deploy the web application and make it accessible via a public link.

## Getting Started
### Prerequisites
- Python 3.x
- Flask
- Render account

### Installation
1. Clone the repository:
        ```bash
        git clone https://github.com/yourusername/flight-fare-prediction.git
        cd flight-fare-prediction
        ```
2. Install the required packages:
        ```bash
        pip install -r requirements.txt
        ```

### Running the Application
1. Run the Flask application:
        ```bash
        python app.py
        ```
2. Access the web application at `http://localhost:5000`.

### Deployment
1. Push the code to a GitHub repository.
2. Connect the repository to Render and deploy the application.
3. Obtain the public link provided by Render.

## API Usage
### `/predict_mobile`
- **Method**: POST
- **Description**: Endpoint for the mobile app to get flight fare predictions.
- **Request Body**: JSON object containing flight details.
- **Response**: JSON object with the predicted fare.

### `/predict`
- **Method**: POST
- **Description**: Endpoint for the web app to get flight fare predictions.
- **Request Body**: JSON object containing flight details.
- **Response**: JSON object with the predicted fare.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.