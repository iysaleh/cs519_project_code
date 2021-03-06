# CS519_ProjectCode
This project is mostly a fork from https://github.com/akosiorek/hart with a few changes. Follow the link to that repository for more information about the KITTI and KTH datasets used in the original project.

## My Experimental Dataset
* Download the Experimental Dataset here (1.3 GB .tar.xz compressed): [Experimental Dataset Google Drive Link](https://drive.google.com/file/d/1uol64kxWbfPgkAf_SMdBESCtJGfmWf6T/view?usp=sharing)
* Note, the images have already been compressed and resized to work with the HART model.

### Successfully Completed Project Goals
* Updated HART code to use newest version of Tensorflow
* Setup runtime environment on Ubuntu
* Evaluated HART on KITTI dataset
* Experimented with HART model on experimental datasets
* Created python script to create GIF demo outputs of images with bounding boxes, glimpses, and attention mechanism location maps
### Attempted & Failed Project Goals (failed code not included in repository!)
* Port HART to work on Windows with Python 3.5
* Port portions of HART to use simpler keras model paradigm
* Create realtime web-cam interface for HART
* Create meaningful improvements for current model by adjusting various hyperparameters
* Recreate Weights file by Retraining model on KITTI dataset
### Desired Project Goals
* Novelty: Implement human-like blink mechanism which refocuses input bounding box at regular intervals to address failure-case when tracked object momentarily ventures off screen. (See section 5.1 in the [final report](https://github.com/iysaleh/cs519_project_code/blob/master/CS519_final_project_report_iysaleh.pdf))--This would be an RNN that does not assume a Markovian state and is fed input from V1 and outputs to the Spatial Attention Mechanism.

