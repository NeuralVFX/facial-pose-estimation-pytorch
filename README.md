![](examples/track_d.gif)
# Face-Pose-Estimation-Pytorch
Training a neural net in Pytorch to generate 3d facial pose estimation from only facial landmarks.

## Notes
- Main code is in [Jupyter Notebook](face_pose_net.ipynb)
- Dataset is generated on the fly using OpenCV
- Output is 51 float values representing blend-shapes for a facial mesh
- Using transfer learning with a pretrained Resnet34
- Training this at 96x96 in order to keep running quick enough for realtime use, quality improves at higher res

## Face Mesh
![](examples/iphone_face_small.jpg)
## Example Training Data
![](examples/git_dataset.png)


## Code Usage
Usage instructions found here: [user manual page](USAGE.md).




