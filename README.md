# Face Mask Detection in Python

This is a README file that provides instructions on how to perform face detection in Python using the OpenCV library.

## Requirements

To run the face mask detection code, you need the following:

1. Python 3.x: Make sure you have Python 3.x installed on your system.
2. OpenCV: Install the OpenCV library by running the following command:

   ```bash
   pip install opencv-python
   ```

## Usage

1. Clone the repository or download the source code files to your local machine.

2. Place the Haar Cascade XML file in the same directory as the Python script.

3. Run the Python script using the following command:

   ```bash
   python face_detection.py
   ```

4. The script will use your computer's webcam to capture video frames. It will then detect faces in real-time and draw rectangles around them.

5. Press 'Q' on your keyboard to quit the application.

## Customization

If you want to customize the face detection parameters, you can modify the following variables in the `face_detection.py` script:

- `scale_factor`: A smaller scale factor will increase the detection speed but may miss some faces. A larger scale factor will be more accurate but slower.
- `min_neighbors`: This parameter specifies how many neighbors each candidate rectangle should have to retain it. Increasing it will result in fewer detections but with higher quality.
- `min_size`: The minimum size of the detected face. Faces smaller than this size will not be detected.

You can experiment with these values to achieve the desired trade-off between detection speed and accuracy.

## References

- OpenCV: [https://opencv.org/](https://opencv.org/)

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it as needed.

![Screenshot 2022-10-12 at 2 09 27 AM](https://user-images.githubusercontent.com/78723011/195432070-1f361799-6455-4127-b586-938a74b7e53a.png)
![Screenshot 2022-10-12 at 2 07 32 AM](https://user-images.githubusercontent.com/78723011/195432216-d4d012bf-2400-4d4b-8273-8739c6198488.png)

## Screen Recording 

https://github.com/IPH-Technologies-Pvt-Ltd/Face-Mask-Detection-Python/assets/126752734/78b171f3-8e6f-4811-85f3-0365c59a12f7


