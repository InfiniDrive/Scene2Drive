# Scene2Drive: Comprehensive Visual Question Answering for Autonomous Driving Multitask Learning


**Scene2Drive** is the first comprehensive VQA dataset for autonomous driving multitask learning, which spans hierarchical scene understanding to interpretable driving decision, covering behavior analysis, motion planning, and vehicle control.

**Scene2Drive** contains 22.7K full-view driving videos and 167K scene-centric QAs and ego-centric QAs, which built upon the widely used open-source outdoor driving dataset nuScenes.


<p align="center">
  <img src="assets/scene2drive.png">
</p>


## Getting Started
### Requirements and Installation
```shell
conda create -n scene2drive python=3.10 -y
conda activate scene2drive
pip install -r requirements.txt
```


### Scene2Drive Dataset
We provide json file with scene-centric QAs and ego-centric QAs from https://pan.baidu.com/s/1mMa6txnfgmvUjGTLjevvPg?pwd=kvbx.

Download the matched raw images from https://www.nuscenes.org/nuscenes.

```Shell
Scene2Drive
├── Dataset
│   ├── scene-centric_QAs.json
│   ├── ego-centric_QAs.json
│   ├── vedio
```

## Visualization Examples

<p align="center">
  <img src="assets/vis.png">
</p>
