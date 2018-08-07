# Udacity_rover_search_sample_return
Udacity's Robotics Software Engineer nano degree Term 1 project 1(Search and Sample return)

### Installation

Setup the python environment to run the simulator and jupyter notebook with the required python packages/modules
[Instructions to setup python environment](https://github.com/udacity/RoboND-Python-StarterKit/blob/master/doc/configure_via_anaconda.md)

Downlaod the rover simulator appropriate for your OS([macOS](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Mac_Roversim.zip), [Linux](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Linux_Roversim.zip),[Windows](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Windows_Roversim.zip))

**Training / Calibration**  

* Download the rover simulator and record data in "Training Mode"
* Launch the jupyter notebook inside the code folder and click on the .ipynb extension file.
* There is already prerecorded data inside **./data** folder
* PLace your recorded data in any folder to run the notebook functions on your data.
* The data path should be updated in the notebook
```
path = '../test_dataset/IMG/*'
```

### Notebook analysis
Once the notebook run each cell at once or all of them to check the ouput, the output video will be placed in the ./output folder
under name 'test_mappingrec.mp4'

If running on different dataset and want to create a new output file remane here in cell 16
```
output = '../output/test_mappingrec.mp4'
```

* **obstacle identification**

* **rock sample identification**

* **process_image()** contents how the worldmap is populated and video output

### Autonomous navigation and mapping

* **perception_setp()** 

* **decision_step()**

### Simulator settings
