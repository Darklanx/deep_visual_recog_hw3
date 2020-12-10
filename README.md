# deep_visual_recog_hw3

## Reproduce
### Requirements
Please first run `pip3 install -r requirements.txt` to make sure all packages required are properly installed.

### Training
To reproduce you have to specify path to your datasets, 
by **modifying variable **ROOT** in `hw3.py` line 34**, to the path to the folder containing your dataset folder,
and the structure of root should look like
```
root
├── dataset
│   ├── train_images
│   ├── pascal_train.json
│   ├── test.json
│   └── test_images
└── logs
```
The structure is already created in this repository, you can choose to simply put train_images and test_images to their respective folders.

After including the images, simply run `python3 hw3.py` then the program will start to train for 40 epochs, which should have the similar result to the one uploaded to the google drive. 
If you want to modify the number of epochs, please modify **line 271** in `hw3.py`. 
### testing
To produce the json for submission, simply run `python3 hw3.py --test <epoch>`, where `<epoch>` specify the number of epoch that the model is trained with, and a json file `0616215.json` will be created.
