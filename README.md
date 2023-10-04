# uav_det
UAV detection under yolov8<br>
The dataset is avaliable in https://github.com/Jake-WU/Det-Fly.<br>
Fyi, the dataset need to be splited manually<br>
# IMPORTANT
This is the code for UAV detection, and implement Loss Landscape in YOLOv8.<br>
This a unclean code for generating loss landscape. You need to modified some code in your scienario.<br>
If the code does not work due to version update, here are some following steps you could reproduce the code: <br>
<1> modified the validators -> get the loss value <br>
<2> run model.val -> get the direction dictionary <br>
<3> run the main.py in the file PlotLoss. <br>

# Excellent thanks in Object detector:
https://github.com/ultralytics/ultralytics

# Excellent thanks in Loss Landscape：
https://github.com/ma-xu/pointMLP-pytorch/issues/42

# Citation
If you use our implementation of Loss Landscape in YOLOv8
plz cite our work, thanks!

@article{laiyolov8inter2023,<br>
  title={YOLOv8-lite: An Interpretable Lightweight Object Detector for Real-Time UAV Detection},<br>
  author={Hawking Lai, Bowie Liu, Ho Yin Kan, Chan-Tong Lam, Sio Kei Im},<br>
  journal={Radioelectronics and Communications Systems},<br>
  year={2023}<br>
}
