# uav_det
UAV detection under yolov8<br>
The dataset is avaliable in https://github.com/Jake-WU/Det-Fly.<br>
Fyi, the dataset need to be splited manually<br>
# IMPORTANT
This is the code for UAV detection, and implementing Loss Landscape in YOLOv8.<br>
This is an unclean code for generating a loss landscape. You need to modify some code in your scenario.<br>
If the code does not work due to version update, here are some following steps you could reproduce the code:<br>
<1> modified the validators -> get the loss value<br>
<2> run model.val -> get the direction dictionary<br>
<3> run the main.py in the file PlotLoss.<br>

# Excellent thanks in Object detector:
https://github.com/ultralytics/ultralytics

# Excellent thanks in Loss Landscape：
https://github.com/ma-xu/pointMLP-pytorch/issues/42

# Citation
If you use our implementation of Loss Landscape in YOLOv8<br>
plz cite our work, thanks!<br>

@inproceedings{laiyolov8inter2023,<br>
  title={YOLOv8-lite: An Interpretable Lightweight Object Detector for Real-Time UAV Detection},<br>
  author={Hawking Lai, Bowie Liu, Ho Yin Kan, Chan-Tong Lam, Sio Kei Im},<br>
  booktitle={2023 IEEE 9th International Conference on Computer and Communications (ICCC)},<br>
  year={2023},<br>
  organization={IEEE}<br>
}
