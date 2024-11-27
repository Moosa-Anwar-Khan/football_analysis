# Football Analysis Project

Here's a possible README structure with content based on the provided GitHub repo:

### Project Overview  
This project analyzes football videos using computer vision and machine learning techniques. Key components include YOLO for object detection, K-means for player clustering, optical flow for motion tracking, and perspective transformation for accurate movement analysis. The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. We will also train the model to improve its performance. Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered. This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.

![Screenshot](output_videos/screenshot.png)

### Features  
- Detects players, referees, and the ball.  
- Uses K-means clustering for team identification.  
- Tracks player speed and distance.  
- Implements YOLOv5 for object detection.

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas

### Changelog  
- **v1.0**: Initial release with player detection and tracking features.

### Installation Instructions  
1. Clone the repository: `git clone <repo_link>`  
2. Install dependencies: `pip install -r requirements.txt`  
3. Set up YOLOv5.

### License  
[MIT License](https://github.com/Moosa-Anwar-Khan/football_analysis/blob/main/LICENSE)

#### Code of Conduct
Code of Conduct sets the standards for how we interact with each other. It is important to maintain a respectful and inclusive environment in order to nourish cooperation. You can read the full document [here](https://github.com/Moosa-Anwar-Khan/football_analysis/blob/main/CONDUCT.md)

### Contribution Guidelines  
1. Fork the repo.  
2. Create a feature branch.  
3. Open a pull request.

### Acknowledgments  
Thanks to Abdullah Tarek for his contributions to this project [GitHub repo](https://github.com/abdullahtarek/football_analysis).