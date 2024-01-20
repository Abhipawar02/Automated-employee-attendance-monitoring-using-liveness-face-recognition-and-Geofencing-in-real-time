# Automated-employee-attendance-monitoring-using-liveness-face-recognition-and-Geofencing-in-real-time
Marking fake attendance is a common problem in traditional attendance tracking systems, especially in large organizations where it is difficult to manually monitor each employee. To address the issue of spoofing or impersonation via photos or videos for fake attendance, a system has been devised. It mandates employees to be physically present within a specific geographical area before utilizing facial recognition for attendance marking. A custom dataset has been created for training the anti-spoofing model. The MobileNetV2 architecture is utilized to train the model and decrease the amount of parameters and computations necessary, all while preserving high accuracy. The liveness detection model ensures that only real faces are recognized, preventing spoofing attempts. By combining liveness facial recognition with geofencing, organizations can ensure that only authorized individuals can access a specific area, and that they are physically present.

## Getting Started

### Prerequisites

- Python 3.9.13

### Running the Script

1. Clone the repository: `git clone https://github.com/Abhipawar02/Automated-employee-attendance-monitoring-using-liveness-face-recognition-and-Geofencing-in-real-time` 
2. Navigate to the project directory: `cd Automated-employee-attendance-monitoring-using-liveness-face-recognition-and-Geofencing-in-real-time`
3. Create a Virtual ENV: `conda activate venv`
4. Install required libraries: `pip install -r requirements.txt`
5. Run the script: `python run main.py`

