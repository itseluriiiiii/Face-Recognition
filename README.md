# Face Recognition System

This is a simple Face Recognition project where you can upload a reference image (ref) and try the code to recognize faces from other images.
Features
1. Upload a reference image (ref) of a person's face.
2. Compare other images to check for matches.
3. Fast and accurate face recognition using advanced algorithms.
4. Easy-to-use web interface.

## Installation

git clone https://github.com/yourusername/face-recognition-app.git.
cd face-recognition-app.

```bash
pip install -r requirements.txt
```

## Usage

```python
Run the Application
Start the app by running the main script:

bash
Copy code
python app.py
Upload Reference Image
Open the app in your browser at http://127.0.0.1:5000/.

Use the upload form to upload a reference image (ref).
Test the Code

Upload another image to check if the face matches the ref image.
Results will be displayed on the web interface.
```

## Contributing
Credits
Libraries Used: OpenCV, face_recognition, Flask.

## Example Output
Success: "Face Matched!" The uploaded image matches the reference image.
Failure: "No match found". The uploaded image does not match the reference image.
