# IF2022-ros-sensors-workflow

1.  On the Surface Go: 
	1. Open PowerShell
	2. `cd C:\ros2_ws` 
	3. `.\install\setup.ps1` 
	4. `ros2 run webcam_publisher pub` 
2. On the left Ailenware: 
	1. Open PowerShell 
	2. `cd C:\Users\engr-ugaif\ros2_ws`
	3. `.\install\setup.ps1` 
	4. `python3 src\ros2_mediapiper\scripts\hand_detector.py`
	5. idk: `ros2 topic echo /image_raw`
	6. 