


# ⚽ Soccer Analytics - AI-Based Detection & Visualization

This repository provides AI-powered soccer analysis through player detection, team classification, key point tracking, and spatial analysis.

## 🔍 Model Details
The Player Detection and Key Point Detection models have been trained using Roboflow's dataset and uploaded to Roboflow Universe:

| Model                                    | mAP    | Precision | Recall |
|------------------------------------------|--------|-----------|--------|
| Player Detection (Football-AI 2)         | 90.9%  | 89.2%     | 89.1%  |
| Key Point Detection (Football Field Detection 1) | 99.5%  | 99.8%     | 100%   |

### Custom Training:
- I have used Roboflow's dataset for training my models.
- You can train your own custom model using the same dataset with a Roboflow account and your API key.
- Training templates are available in the notebooks folder.

## 📹 Video Demonstrations

### 1️⃣ Input Video
This is the raw input video before any AI-based processing. It captures a soccer match with players moving dynamically on the field. This input serves as the base for further detection, classification, and analysis using deep learning models.

[Watch the Input Video](https://github.com/user-attachments/assets/ceedfd70-62d5-44b1-afe3-f7b11e5febc9)

### 2️⃣ Player Detection
The YOLOv8x-based player detection model identifies and tracks all players on the field in real time. Each player is highlighted with bounding boxes, allowing precise movement analysis. This serves as the foundation for further classification and tactical insights.

[Watch Player Detection](https://github.com/user-attachments/assets/8ec64fce-6b3e-45dd-9b45-b342d5d6994e)

### 3️⃣ Team Classification
Once players are detected, this model classifies them into teams based on jersey colors. Using a color-based clustering approach, players are assigned to their respective teams, helping analyze team formations, marking strategies, and player distribution during gameplay.

[Watch Team Classification](https://github.com/user-attachments/assets/d833594d-ddd6-44b3-b97b-64671a893a23)

### 4️⃣ Key Point Detection
This video demonstrates detection of key landmarks on the soccer field, such as center lines, penalty areas, and goalposts. These field landmarks are crucial for spatial awareness, helping measure player positions relative to key game zones like the penalty box, midfield, or goal area.

[Watch Key Point Detection](https://github.com/user-attachments/assets/3dbca5e4-ffb2-46fd-bc0a-20f83682fd7f)

### 5️⃣ Player Detection & Radar View
This visualization combines player detection with a radar-like view to show real-time player positions across the field. The radar overlay provides a bird's-eye perspective, helping in strategic planning by analyzing spacing, movement trends, and team shape.

[Watch Player Detection & Radar View](https://github.com/user-attachments/assets/9ba85e2a-8957-4104-ae50-59386fa3abd0)

### 6️⃣ Voronoi Diagram for Player Positioning
A Voronoi diagram is used to divide the field into zones based on player positions. Each player controls a unique area, and this method helps analyze space utilization, defensive coverage, and passing opportunities. It is a key component in tactical decision-making for formations and player roles.

[Watch Voronoi Diagram for Player Positioning](https://github.com/user-attachments/assets/e0c7af77-1cce-4d08-a8e0-06801deddc44)

## 🚀 How to Use?
To run this project, use `Football Analysis.ipynb` in the notebooks folder.

### Steps:
1. Open the notebook in Google Colab (T4 GPU runtime).
2. Run the required cells to generate different outputs.
3. To use a different video, update the source video path in the download section.

## 💡 Suggestions & Contributions
If you have ideas for improvement, feel free to open an issue or submit a pull request. 🚀


