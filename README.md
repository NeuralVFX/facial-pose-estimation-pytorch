![](examples/track_d.gif)
# Face-Pose-Estimation-Pytorch
Training a Neural Net in Pytorch to generate 3d facial pose estimation from only facial landmarks.

## Notes
- Main code is in [Jupyter Notebook](face_pose_net.ipynb)
- Training data is artificially generated on the fly using OpenCV
- Output is 51 blend-shape float values which can be applied to a face mesh
- This only outputs blend-shape values, head transform is handled by a separate part of the pipeline

## Training Pipeline Example
![](examples/pytorch_training_pipeline.png)
## Inference Pipeline Example
![](examples/pipeline.png)
## Artificial Data-Pair Examples
![](examples/git_dataset.png)

## Code Usage
Usage instructions found here: [user manual page](USAGE.md).




