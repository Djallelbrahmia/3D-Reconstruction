
## Description

This project implements a 3D reconstruction pipeline using computer vision techniques. It processes multiple images to extract depth information and generate a point cloud representation of the scene. The key steps involve feature detection, matching, pose estimation, triangulation, and reprojection error analysis.

## Features

- **Image Matching**: Detects and matches keypoints across multiple images.
- **Pose Estimation**: Estimates camera pose using the Perspective-n-Point (PnP) algorithm with RANSAC.
- **Triangulation**: Calculates 3D points from 2D correspondences across images.
- **Point Cloud Generation**: Outputs a 3D point cloud in PLY format that can be visualized using 3D software.

## Requirements

To run this project, you need to have the following Python packages installed:

```plaintext
numpy
opencv-python
tqdm
```

You can install these dependencies using pip:
```plaintext
pip install -r requirements.txt
```

##Usage
Clone the repository:
```plaintext
git clone https://github.com/Djallelbrahmia/3D-Reconstruction.git
cd 3D-Reconstruction
```

Run the main script:

Modify the paths in the main script to point to your images and execute it to generate the point cloud.

Visualize the output:

The generated point cloud will be saved as a .ply file in the res directory. You can visualize it using software like MeshLab or CloudCompare.
