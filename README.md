# Depi-Aws-ML-project
Face Detection with Amazon Rekognition  This project demonstrates how to use **Amazon Rekognition** for facial detection. It includes creating a face collection, uploading and managing faces, detecting faces in images, and cleaning up resources. Designed for learning and exploring computer vision capabilities in AWS. 


# Computer Vision Face Detection Lab

This project demonstrates how to use **Amazon Rekognition** to perform facial detection. The notebook guides users through a series of steps to create and manage a facial recognition collection using AWS tools.

## Features
The lab covers the following tasks:
1. **Create a Collection**: Set up a collection in Amazon Rekognition.
2. **Upload and Manage Faces**:
   - Add an image of a face to the collection.
   - View the bounding box created for the image.
   - List the faces in the collection.
3. **Face Detection**:
   - Use the collection to detect a face.
   - Display the bounding box of the detected face.
4. **Delete the Collection**: Clean up by deleting the collection when finished.

---

## Prerequisites
Before running this project, ensure the following:
- **AWS Account**: Access to Amazon Rekognition service.
- **AWS CLI Configuration**: Set up credentials for the AWS SDK for Python (Boto3).
- Python packages:
  - `boto3`
  - `skimage`
  - `matplotlib`
  - `numpy`
  - `PIL`

## Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install the required Python packages:
   ```bash
   pip install boto3 numpy scikit-image matplotlib pillow
   ```

## Running the Notebook
1. Start a Jupyter Notebook environment.
2. Open the file `05-facedetection.ipynb`.
3. Follow the step-by-step instructions provided in the notebook.

## Example Output
The notebook will guide you through creating a Rekognition collection, uploading a face image, and detecting the face. Below is an example output:
```
Collection ARN: aws:rekognition:<region>:<account_id>:collection/Collection
Status Code: 200
Done...
```

## Cleanup
To avoid unnecessary costs, ensure you delete the created collection after completing the lab.

---

## Future Improvements
- Extend functionality to detect multiple faces in a single image.
- Integrate face comparison features for additional use cases.
- Automate the setup process with CloudFormation or similar tools.

