# Action Recognition

#### It is revealed that this project is based on [Open MMProject](https://github.com/open-mmlab).
#### This Project's Goal is to Apply Action Recognition with Multi GPU and TensorRT.
<br></br>

## Configuration

The configuration is as follows  
1. preprocessing : we offer merge dataset(pkl file) function
2. visualization : we offer visualization of confidence score map which is input of posec3d
3. inference : we offer demo, inference on single gpu, inference on multi gpu with tensorRT and Flask
<br></br>
> #### we modify and custom mmaction2, mmpose, mmdetection project's some part about detection target to use the tensorRT and multi gpu.   

## Result

#### 1) Visualization of Confidence Map with visualization/get_confmap.py
<br></br>
<p align="center"><img src="https://user-images.githubusercontent.com/63839581/187403723-d0e5895d-ce02-47b6-8651-1800b48a9f07.jpg" width=500 height=700></p>
<br></br>

#### 2) Visualization of Demo Video with ./demo.py
<br></br>
<p align="center"><img src="https://user-images.githubusercontent.com/63839581/187407691-52634b53-960b-4ae0-a6e3-9888bd54e127.gif" width=800 height=500></p>
<p align="center"><img src="https://user-images.githubusercontent.com/63839581/187407703-087c6474-e5fe-4360-9471-7776a81ca509.gif" width=800 height=500></p>
<p align="center"><img src="https://user-images.githubusercontent.com/63839581/187407442-f0c493c4-a36e-48ae-bdd7-d4836c4561b1.gif" width=800 height=500></p>
