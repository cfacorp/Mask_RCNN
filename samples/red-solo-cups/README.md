# Finding Red Solo Cups

Usage: import the module (see Jupyter notebooks for examples), or run from
       the command line as such:

    # Train a new model starting from pre-trained COCO weights
    python3 redcup.py train --dataset=/path/to/redcup/dataset --weights=coco

    # Resume training a model that you had trained earlier
    python3 redcup.py train --dataset=/path/to/redcup/dataset --weights=last

    # Train a new model starting from ImageNet weights
    python3 redcup.py train --dataset=/path/to/redcup/dataset --weights=imagenet

    # Apply color splash to an image
    python3 redcup.py splash --weights=/path/to/weights/file.h5 --image=<URL or path to file>

    # Apply color splash to video using the last weights you trained
    python3 redcup.py splash --weights=last --video=<URL or path to file>

