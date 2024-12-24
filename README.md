# Custom facial recognition using Eigen Faces and pca 
starts by creating custom dataset (add several faces for accurate recognition) using face detection \
dataset is grayscale images of faces only\
dataset is then resized to 100px,100px\
saves flatened images into a numpy array\
creates eigen faces and standarizes the data\
trains an svm model\
live test is included 
# libraries needed
```python
pip install opencv-python numpy matplotlib scikit-learn pandas
```

# download facial detection model
haarcascade_frontalface_default.xml
