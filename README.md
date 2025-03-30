# Cardiovascular Detection using ECG Images

A Streamlit app for cardiovascular disease prediction using ECG images.

## Project Structure
- **Deployment/**: Contains the files needed for deployment on Render.
  - `Dockerfile`: Docker configuration for the app.
  - `Ecg.py`: ECG processing and prediction logic.
  - `final_app.py`: The main Streamlit app.
  - `requirements.txt`: Python dependencies.
- **model_pkl/**: Contains the trained model files (stored in Git LFS).
  - `Heart_Disease_Prediction_using_ECG (4).pkl`: Trained model for ECG classification.
  - `PCA_ECG (1).pkl`: PCA model for dimensionality reduction.

## Deployment
This app is deployed on Render using Docker. To deploy:
1. Push the code to GitHub.
2. Create a new Web Service on Render.
3. Select the repository and set the root directory to `Deployment`.
4. Deploy the app.

## Local Setup
To run the app locally:
1. Navigate to the `Deployment` folder.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the app: `streamlit run final_app.py`

## Requirements
- Python 3.8
- Streamlit
- Other dependencies listed in `requirements.txt`