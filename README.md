# SpudScan-Project
Potato Disease Classification with help of Machine Learning Algorithm

# Steps Involved:
For Python
1. Installing Python and its packages using pip
2. Install Tensorflow serving

for ReactJS   
1. Install Node.JS using npm
2. Install dependencies

Training Model

1. Get the data from https://www.kaggle.com/datasets/arjuntejaswi/plant-village
2. Run Jupyter Notebook and open potato-disease-training.ipynb.
3. Run all cells sequentially.
4. Save the generated model in the models folder with a version number.

Running the API

Using FastAPI

1. Navigate to the api folder.
2. Run FastAPI server using uvicorn main:app --reload --host 0.0.0.0.

Using FastAPI & TF Serve

1. Navigate to the api folder.
2. Copy models.config.example as models.config and update paths.
3. Run TensorFlow Serving using Docker.
4. Run FastAPI server using uvicorn main-tf-serving:app --reload --host 0.0.0.0.

Running the FrontEnd

1. Navigate to the frontend folder.
2. Copy .env.example to .env and update API URL.
3. Run the frontend using npm run start.


   
