# blueberry_segmentation

Blueberry segmentation with Pytorch using Deep Blueberry data.

Database link: https://ieee-dataport.org/documents/deepblueberry-quantification-blueberries-wild-using-instance-segmentation#files.

The UNET architecture implementation was taken from https://github.com/usuyama/pytorch-unet.

I would suggest running the code in Colab, but have also included a .py file if anybody wants to train on their own machine. Also, much of my preprocessing code is very messy, I'm currently working on cleaning it up.

**HOW TO START (on Colab)**

1. Download the blueberry image segmentation database via this link: https://drive.google.com/drive/folders/1mfut4v34ou5qSC5bW_cxlAlRKpJXDHDZ?usp=sharing
2. Upload the files to your Google Drive.
3. Change the BASE_DIR path constant in Colab so that it reflects wherever you uploaded the database.

That's it. If you want to add more testing images, feel free to find some on Google and dragging it into the Deep_BlueBerry_databases/instancesegmentatio/test/ folder.

TODO:
- Make predictions more modular. IE not displaying just one prediction.
- Make augmentations more drastic.
- Adjust hyperparameters.
