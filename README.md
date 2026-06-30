# Eye Disease Detection using Deep Learning

## Project Overview
Eye Disease Detection is a web application developed using Deep Learning to identify common eye diseases from uploaded eye images. The application provides disease prediction along with a brief description of the detected condition.

## Features
- Upload an eye image for disease detection
- Predicts common eye diseases using a trained Deep Learning model
- Displays the predicted disease with a description
- Simple and user-friendly web interface
- Camera capture support for real-time image prediction

## Technologies Used
- Python
- Flask
- TensorFlow / Keras
- OpenCV
- NumPy
- HTML
- CSS

## Project Structure

```
Eye Disease Detection/
│
├── app.py
├── predict.py
├── model_engine.py
├── preprocessor.py
├── templates/
├── uploads/
├── eye_project.db
└── README.md
```

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Place the trained model file (`eye_disease_model.h5`) in the project folder.
4. Run the application using:

```
python app.py
```

5. Open your browser and visit:

```
http://127.0.0.1:5000
```

## Model Information

The trained model file (`eye_disease_model.h5`) is **not included** in this repository because its size exceeds GitHub's file size limit.

## Future Enhancements

- Improve model accuracy
- Support additional eye diseases
- Cloud deployment
- User authentication and patient history

## Author

**Dharanya**

B.Sc. Information Technology Graduate
