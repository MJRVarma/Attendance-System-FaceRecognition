# **Attendance System based on FaceRecognition**

This code implements an Attendance System that uses facial recognition to identify students and mark their attendance. The system uses a pre-trained face recognition model to recognize the students and a machine learning model to predict their names.

The system works by capturing the student's image through a webcam, detecting the face in the image using MTCNN, and then embedding the face using the Facenet model. The embedded face is then passed through the machine learning model, which predicts the name of the student.

If the student's name is successfully predicted, their attendance is marked in a CSV file that is saved in the 'Attendance' directory.

Here we used MTCNN , The MTCNN (Multi-Task Cascaded Convolutional Networks) is a face detection model that is capable of detecting multiple faces in a single image or frame. This makes it useful for applications such as attendance systems, where multiple people need to be identified and their attendance recorded at the same time. MTCNN works by first detecting the face in an image, then refining the detection using a series of neural networks. It can detect faces at different scales and orientations, making it robust to variations in lighting and pose.

# **Installation**

To run this code, you will need to install the following dependencies:

  Python 3.6 or higher
  OpenCV
  MTCNN
  scikit-learn
  Pandas
  Numpy
  Tensorflow
  Keras
  
You can install these dependencies using pip, by running the following command:
  pip install opencv-python mtcnn scikit-learn pandas numpy tensorflow keras
  
# **Usage**

Clone this repository to your local machine:

    git clone https://github.com/<username>/attendance-system.git

Run the "Taking Photos(Training).ipynb" notebook to capture images of the people you want to recognize and train the model.

After training the model, run the "attendance.ipynb" notebook to start the attendance system.

When the notebook starts, it will open your webcam, and start detecting faces in real-time. If a face is detected, the system will compare it to the faces in the database, and mark the attendance of the corresponding person.

To exit the system, press the "Esc" key.

  
Follow the instructions in the Jupyter Notebook to start the Attendance System.

## Contributors :
  Jagannadha Rohit Varma Mandhapati
  
  Contributions are welcome! If you would like to contribute to this project, please feel free to fork the repository and submit pull requests with your changes. We appreciate any help and feedback from the community.
  

