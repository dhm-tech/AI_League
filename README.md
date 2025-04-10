# VisionFit

## About the Project
A smart system based on artificial intelligence and virtual reality to analyze and improve boxers' training performance.
The system tracks and analyzes boxers' movements using computer vision, providing immediate feedback and intelligent recommendations to improve combat strategy and reduce injuries.

## Objectives
- Provide an accurate analysis tool for boxing movements.
- Improve boxers' performance by providing immediate instructions.
- Support coaches with detailed statistics to track progress.

## Technologies Used
- Python, MediaPipe, and OpenCV for motion analysis.
- Plotly and Streamlit for interactive dashboard design.
- Figma website simulation design.

## How to Use
- There are two files in this project. The first, AI_CameraLive, opens the camera directly for the boxer, allowing him to practice punch types, identify the angles and speed of his punch, and classify them.
- In the second file, AI_VideoTest, the model automatically identifies the punch type by attaching a video link to the boxer's movements. This helps identify punch types and avoid any errors that may occur during training.

## General Notes
- This project represents the initial phase (MVP) of 30% of the full concept. We are currently focusing on proving the feasibility of real-time analysis and classification using the camera. The project is still in the experimental phase, and if successful, it will be further developed to include advanced features such as virtual reality (VR), an interactive virtual opponent, and direct connectivity with smart training platforms to enhance the entire boxer's experience.
- In the AI_VideoTest file, you will see the outputs inverted. This is due to the values ​​of the x and y axes. We are currently focusing on the final output, after which we will address improvements, additions, and developments, as mentioned previously.

## Running the Project
- The AI_CameraLive file can be played normally and the camera will open directly if the device supports it.
- The AI_VideoTest file requires a clip showing the player's performance so the model can analyze it. It can be added under the comment within the file (put the video path here).

## Team Members
- Sultana Zagzoog
- Shaymaa Al-Zahrani
- Yousef Batawq
- Abdulrahman Qutah
