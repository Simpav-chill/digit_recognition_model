# Description
This is a simle study project to understand the model training flow. This model was trained with MNIST dataset from torchvision python library. 

The final recognition accuracy is 98%, the average loss is 0.0148.

I was following the [YouTube video tutorial](https://www.youtube.com/watch?v=vBlO87ZAiiw).

# Tech stack
Language – python 3.14.6.

Libraries:
- torch
- torchvision
- matplotlib

# Launch
To launch the code you must have installed [Anaconda distribution or miniconda](https://www.anaconda.com/download/success?reg=skipped).

## Clone the repository

``` bash
git clone https://github.com/Simpav-chill/digit_recognition_model
```

## Install dependencies if they're not installed

Use this, if you have nvidia gpu:
``` bash
python -m pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu128
python -m pip install matplotlib
```

It's going to install gpu-enabled version of pytorch.

OR

Use this if you don't have nvidia gpu:
``` bash
python -m pip install torch torchvision matplotlib
```

## Launch jupiter notebook

Open Anaconda Prompt and enter this:
``` bash
jupyter notebook
```

## Launch the file

Change directory to the repository directory and open the .ipynb file.

Press the button "Restart the kernel and run all cells" at the top. 

Now you can see the model training and checking its work.
