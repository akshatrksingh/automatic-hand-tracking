# Automatic Hand Tracking

## Project Overview

This project implements an automatic hand tracking pipeline using advanced computer vision techniques. By combining Google MediaPipe for hand detection and SAM 2 (Segment Anything Model) for segmentation, the system can track and mask hand movements in video frames.

## Key Features

- Hand detection in initial video frame
- Automatic hand tracking across video sequence
- Mask generation for hand regions
- Compatible with multiple hand tracking scenarios

## Technologies Used

- Python
- OpenCV (cv2)
- Google MediaPipe
- SAM 2 (Segment Anything Model)
- PyTorch

## Quick Highlights

The solution is implemented in `final_solution.ipynb`, providing a Jupyter notebook that demonstrates the entire hand tracking workflow. 

### Mac Users Note

For macOS users, the original `misc.py` decoder logic has been replaced with OpenCV-based implementation to ensure compatibility.

## Getting Started

1. Clone the repository
2. Install requirements using `pip install -r requirements.txt`
3. Run the Jupyter notebook `final_solution.ipynb`

## Sample Output

The project generates a video with masked hand movements, showcasing the tracking capabilities across different frames.

## Project Structure

- `final_solution.ipynb`: Main implementation notebook
- `requirements.txt`: Project dependencies
- Sample images and output video included

## Contributions

Feel free to fork, explore, and contribute to the project!
