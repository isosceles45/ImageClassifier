# Image Classification with SVM and Wavelet Transform

![Screenshot 2024-07-20 173102](https://github.com/user-attachments/assets/bb0f68fd-7a1d-4ac0-9073-a0140e86b4bf)

Image classification is the task of assigning a label or a category to an input image. It is a fundamental problem in computer vision, and it has many applications in various fields. Support Vector Machines (SVM) is one of the popular algorithms used for image classification. SVM is a machine learning algorithm that can be used for both classification and regression tasks. It has shown promising results in many applications, including image classification.

Wavelet transform can be used in image classification tasks by extracting relevant features from an image at multiple scales. The wavelet transform decomposes an image into multiple levels of frequency sub-bands, which contain information about different aspects of the image such as edges, textures, and smooth regions.

Several libraries can be used for wavelet transform and image classification. One popular library for wavelet transformation is PyWavelets, and for image classification, we can use scikit-learn.

## Project Steps

### 1. Data Collection
We will collect a dataset of images that are to be classified.

### 2. Data Pre-processing
We will pre-process the images to extract relevant features using OpenCV.

### 3. Training the SVM Classifier
We will train an SVM classifier using the extracted features from the training dataset.

### 4. Testing the Classifier
We will test the performance of the SVM classifier on a test dataset.

### 5. Evaluation
We will evaluate the performance of the SVM classifier by analyzing its accuracy and confusion matrix.

## Libraries and Tools
- **Wavelet Transform:** [PyWavelets](https://pywavelets.readthedocs.io/en/latest/)
- **Image Classification:** [scikit-learn](https://scikit-learn.org/)
- **Image Processing:** [OpenCV](https://opencv.org/)

## Example Workflow
1. **Data Collection:** Gather images from a reliable source.
2. **Data Pre-processing:**
    - Load images using OpenCV.
    - Apply wavelet transform to extract features.
3. **Training the Classifier:**
    - Split the dataset into training and testing sets
    - Train the SVM classifier using scikit-learn.
4. **Testing the Classifier:** Evaluate the classifier on the test dataset.
5. **Evaluation:** Calculate accuracy and confusion matrix to assess performance.

