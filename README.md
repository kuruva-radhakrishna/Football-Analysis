To structure your README like the image, I'll incorporate the following improvements:

Better sectioning with bold titles and descriptions.
Code formatting using Markdown's code blocks.
Inline badges for modes (e.g., PITCH_DETECTION in a gray badge).
Better visual hierarchy with bullet points and improved spacing.
Embedded video or image previews below the corresponding explanations.
Here’s an updated version of your README:

⚽ Football AI Video Analysis
Overview
This project focuses on AI-driven analysis of football videos, including ball tracking, player detection, team classification, and tactical insights.

🚀 Features
🎯 Ball Tracking – Detect and track the ball in real time.
🏃 Key Point Detection – Identify key points on players for movement analysis.
⚽ Player and Ball Detection – Detect both players and the ball on the pitch.
📊 Voronoi Team Control – Visualize team control over different pitch areas.
🏅 Team Classification – Classify players based on their teams.
📡 Radar View – A tactical representation of player positions.
🏟️ Pitch Detection – Detect soccer field boundaries and key points.
📽️ Video Demonstrations
Click on the links below to view each feature in action.

📥 Input Video
<video width="800" controls> <source src="https://drive.google.com/uc?id=1-Tl8W59_MTYl73ClplaHfe3LY3_BangS" type="video/mp4"> Your browser does not support the video tag. </video>
🎯 Ball Tracking
BALL_TRACKING - Tracks the ball movement across the pitch.

bash
Copy code
python main.py --source_video_path data/input.mp4 \
--target_video_path data/ball-tracking.mp4 \
--device mps --mode BALL_TRACKING
<video width="800" controls> <source src="https://drive.google.com/uc?id=1-GlNHWsDyfIpGpc4Hku0Z3b2OqN4MI6b" type="video/mp4"> Your browser does not support the video tag. </video>
🏃 Key Point Detection
KEY_POINT_DETECTION - Detects key joints of players for movement analysis.

bash
Copy code
python main.py --source_video_path data/input.mp4 \
--target_video_path data/key-point-detection.mp4 \
--device mps --mode KEY_POINT_DETECTION
<video width="800" controls> <source src="https://drive.google.com/uc?id=1-8aM1QkoWDzKAHgtOimcb25-jqGUSJtC" type="video/mp4"> Your browser does not support the video tag. </video>
⚽ Player and Ball Detection
PLAYER_BALL_DETECTION - Detects all players and tracks the ball.

bash
Copy code
python main.py --source_video_path data/input.mp4 \
--target_video_path data/player-ball-detection.mp4 \
--device mps --mode PLAYER_BALL_DETECTION
<video width="800" controls> <source src="https://drive.google.com/uc?id=1-ESo1PNzpekIitW2LcfeBoJQjPRMOyHj" type="video/mp4"> Your browser does not support the video tag. </video>
📊 Voronoi / Team Control
TEAM_CONTROL - Visualizes team control over the field using Voronoi diagrams.

bash
Copy code
python main.py --source_video_path data/input.mp4 \
--target_video_path data/team-control.mp4 \
--device mps --mode TEAM_CONTROL
<video width="800" controls> <source src="https://drive.google.com/uc?id=1-P9Nnu_vzuRUJk5pC6eCwy2q1duJufn4" type="video/mp4"> Your browser does not support the video tag. </video>
🏟️ Pitch Detection
PITCH_DETECTION - Detects the soccer field boundaries and key points.

bash
Copy code
python main.py --source_video_path data/2e57b9_0.mp4 \
--target_video_path data/2e57b9_0-pitch-detection.mp4 \
--device mps --mode PITCH_DETECTION
<video width="800" controls> <source src="https://drive.google.com/uc?id=1-XYZ123ABC456" type="video/mp4"> Your browser does not support the video tag. </video>
📌 How to Use
Clone this repository.
bash
Copy code
git clone https://github.com/your-repo/football-ai.git
cd football-ai
Install dependencies.
bash
Copy code
pip install -r requirements.txt
Run the main script to process videos.
bash
Copy code
python main.py --source_video_path data/input.mp4 --target_video_path data/output.mp4 --mode BALL_TRACKING
🤝 Contributing
Feel free to open issues or submit pull requests to improve the project.

📜 License
This project is open-source under the MIT License.

This new format aligns with your reference image by:
✅ Using inline mode badges (PITCH_DETECTION, BALL_TRACKING, etc.).
✅ Improving structure and spacing.
✅ Adding better code formatting.
✅ Displaying embedded videos with explanations.

Would you like any further modifications? 😊
