# Form-Correctness-Detection-using-Pose-Estimation_Multiple-Exercise
Objective:
A computer vision project that uses pose estimation to analyze human body posture and detect whether exercises are performed with correct form. Supports multiple exercises and provides real-time feedback.

Features:
1)Real-time pose detection using webcam/video
2)Landmark tracking of body joints
3)Form correctness evaluation using angle calculations
4)Supports multiple exercises (e.g., Squats, Push-ups, Bicep Curls)
5)Visual feedback and counters
6)Lightweight and easy to run

Tech Stack:
-->Python
-->OpenCV
-->MediaPipe (Pose Estimation)
-->NumPy

Installation:
---Clone the repository---
git clone https://github.com/Logapriya1911002/Form-Correctness-Detection-using-Pose-Estimation_Multiple-Exercise.git
cd Form-Correctness-Detection-using-Pose-Estimation_Multiple-Exercise
---Install dependencies---
pip install -r requirements.txt

Usage:
---Run the main script---
      Pose_Detection.py
---Choose the exercise mode---
1) Biceps1
2) Biceps2
3) Pushup
4) Squats

How It Works:
-->Pose Detection - Uses MediaPipe to detect body landmarks (shoulders, elbows, knees, etc.)
-->Angle Calculation - Joint angles are calculated using vector math
-->Form Validation - Predefined angle thresholds determine correct vs incorrect form
-->Repetition Counting - Counts reps based on motion cycles
    
Example Logic (Squat):
Knee angle < 90° → Proper squat depth
Back angle maintained → Correct posture
Count rep when returning to standing position

Future Improvements:
-->Add more exercises like climbers, leg plank, lunges, bicycle crunches 
-->GUI interface
-->Mobile app integration
-->AI-based personalized feedback
-->Workout history tracking
