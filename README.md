# AI_workout_pose_tracker

The AI Workout Pose Detection Model is a real-time fitness assistant that helps users maintain proper workout form and prevent injuries. 
This model detects the human body, identifies key points, and calculates angles to determine if a workout pose is correct. 
It provides instant feedback and tracks repetitions for an accurate and effective workout experience.

Features

-> Real-time Pose Detection: Identifies key body points and tracks movement.

-> Angle Calculation: Analyzes joint angles to ensure correct posture.

-> Instant Feedback: Provides corrective guidance to maintain proper form.

-> Repetition Counter: Tracks the number of valid repetitions.

-> Support for Multiple Exercises: Adaptable to various workout types (e.g., squats, push-ups, lunges).




Technologies Used: Programming Language: Python

Frameworks & Libraries: 
-> OpenCV (Computer Vision)
-> Mediapipe (Pose Detection)
-> NumPy (Mathematical Computations)
-> TensorFlow/Keras (AI-based Enhancements)
-> PyGame (GUI Integration)



Installation

Prerequisites

Ensure you have Python installed (>=3.7). 
Install the required dependencies using:

pip install opencv-python mediapipe numpy tensorflow pygame

or

pip install opencv-python
pip install mediapipe
pip install numpy
pip install tensorflow
pip install keras
pip install pygame


Usage: 

1. Run the Pose Detection Script:  python pose_detection.py

2. Perform Workout Moves

-> Stand in front of the camera and perform the exercise.
-> The model will detect your pose and provide real-time feedback.
-> It will count valid repetitions and alert you if the posture is incorrect.

How It Works

Body Keypoints Detection: The model uses MediaPipe to track key points such as shoulders, elbows, knees, etc.

Angle Computation: Calculates angles between joints to check if the form is correct.

Feedback System: Displays messages and suggestions based on detected posture.

Repetition Tracking: Counts only valid repetitions based on proper movement execution.


Example Output

Correct Pose: "Good job! Keep going."

Incorrect Pose: "Adjust your knee angle. Keep your back straight."

Reps Count: "Reps completed: 5"



Future Enhancements

Integration with AI models for more advanced feedback.

Support for additional workout types.

Mobile application version.

Voice-assisted feedback.

Workout plan suggestion based on goal, interests and healt issues if any



Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

License

This project is licensed under the MIT License.



Contact

For any inquiries or contributions, please contact: laraibnoorien@gmail.com or github.com/laraibnoorien


