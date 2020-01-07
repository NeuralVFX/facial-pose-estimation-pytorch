
## Getting Started
- Check your python version, this is built on `python 3.6`
- Install `pytorch 0.4.1` and dependencies from https://pytorch.org/
- Install packages , `cv2 4.1.1`, `onnx 1.5.0`

- Clone this repo:

```bash
git clone https://github.com/NeuralVFX/face-pose-estimation-pytorch.git
```

## Train The Model
- Run [face_pose_net.ipynb](face_pose_net.ipynb) Jupyter Notebook

## Use The Model
- Take the optimized `ONNX` file from the `/output/`directory
- Load this model in OpenCVs DNN Module


