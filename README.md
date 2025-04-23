# Facials Recognition & Recommendation System

This project uses facial recognition technology and a recommendation system to provide personalized recommendations based on facial data. The system can recognize individual users and suggest relevant items based on their past behavior or preferences.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Deepakshukla241999/fac-reco-recommender.git
    ```

2. Navigate to the project folder:
    ```bash
    cd fac-reco-recommender
    ```

3. Create a virtual environment:
    ```bash
    python -m venv virtualEnviroment
    ```

4. Activate the virtual environment:
    - On Windows:
        ```bash
        .\virtualEnviroment\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source virtualEnviroment/bin/activate
        ```

5. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

After setting up the environment, run the application as follows:

1. Run the facial recognition script to add users and capture their data.
    ```bash
    python facial-recognition/add_user.py
    ```

2. Start the recommendation system.
    ```bash
    python recommendationSystem/recommend.py
    ```

3. The system will identify the user based on facial recognition and provide personalized recommendations.

## Project Structure

The project consists of the following folders:

- **facial-recognition/**: Contains code and models for facial recognition.
- **recommendationSystem/**: Includes the recommendation algorithm and user preferences.
- **shared-data/**: Stores any shared data such as datasets and model weights.
- **virtualEnvironment/**: Contains the virtual environment used for the project.
- **requirements.txt**: Lists the required Python dependencies.

## Technologies Used

- **Python**: The main programming language used.
- **OpenCV**: For computer vision tasks.
- **Face Recognition**: For recognizing and processing faces.
- **Scikit-learn**: For machine learning algorithms.
- **Flask**: For web framework (if applicable).
- **Pandas**: For handling data.
- **NumPy**: For numerical computations.

## License

This project is licensed under the MIT License - see the LICENCE file for details.
