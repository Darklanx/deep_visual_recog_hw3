# deep_visual_recog_hw3

## Reproduce
To reproduce you have to specify path to your datasets, 
by **modifying variable **ROOT** in `hw3.py` line 34**, to the path to the folder containing your dataset folder,
and the structure of root should look like
```
root
├── train_images
│   ├── image 1...
│   └── image 2...
├── test_images
│   ├── image 1...
│   ├── image 2...
│   └── image 3...
├── pascal_train.json
└── test.json
```
The structures are already created in this repository, you can choose to simply put train_images and test_images to their respective folders.
