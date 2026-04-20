# PAFJ-Net

The corresponding paper title for this project is “Poppy Detection Network based on Position-Aware Extraction and Feature Joint Enhancement”.

# Train your net
1.Add the yaml file in the model folder to the YOLOv10 official library;

2.Add the GCFF, PAM, CWConcat, and MJFE modules from PAFJ-Net//models//nn//modules//block.py to your corresponding block.py file, and add content about the GCFF, PAM, CWConcat, and MJFE modules to _init_.py and task.py;

3.You can execute training using the command "yolo detect train data=cfg your data.yaml model=your model.yaml epochs=300 batch=32 imgsz=640".

# Datasets

https://universe.roboflow.com/poppy-nm40w/my-first-project-xg0qx
