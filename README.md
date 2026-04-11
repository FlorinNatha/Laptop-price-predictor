# Laptop Price Predictor

A machine learning project that predicts laptop prices based on various features. The project includes a trained model and a web application for easy price prediction.

## Project Structure

- `model/`: Contains the machine learning model and training notebook
  - `model building.ipynb`: Jupyter notebook for model training
  - `predictor.pickel`: Trained model file
- `website/`: Web application built with Flask
  - `app.py`: Main Flask application
  - `requirements.txt`: Python dependencies
  - `static/`: CSS and other static files
  - `templates/`: HTML templates
  - `Dockerfile`: For containerization
  - `Procfile`: For deployment (e.g., Heroku)

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd Laptop-price-predictor
   ```

2. Set up the Python environment:
   ```
   python -m venv env
   env\Scripts\activate  # On Windows
   pip install -r website/requirements.txt
   ```

## Usage

### Running the Web Application

1. Navigate to the website directory:
   ```
   cd website
   ```

2. Run the Flask app:
   ```
   python app.py
   ```

3. Open your browser and go to `http://localhost:5000`

### Using the Model Directly

The trained model is available in `model/predictor.pickel`. You can load it in Python using pickle and make predictions.

## Model Training

To retrain or modify the model, open `model/model building.ipynb` in Jupyter Notebook and run the cells.

## Deployment

The project includes a Dockerfile for containerization and a Procfile for platforms like Heroku.

## Dependencies

All Python dependencies are listed in `website/requirements.txt`. Install them using:
```
pip install -r website/requirements.txt
```

## Contributing

Feel free to submit issues and pull requests.

## License

This project is open source. Please check the license file for details.
