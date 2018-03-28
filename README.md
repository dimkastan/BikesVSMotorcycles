# RaccoonsVsCats-  For those who are tired watching cats vs dogs examples
Download Images from Google Image search using selenium and train your custom classifier to distinguish raccoons vs cats using PyTorch 
<br />
*Please read the disclaimer before proceeding


## Prerequisites
You need to install Anaconda for Python 3. <br/>
My version is:

    Python 3.6.0 |Anaconda 4.3.1 (64-bit)| (default, Dec 23 2016, 12:22:00) 
    [GCC 4.4.7 20120313 (Red Hat 4.4.7-1)] on linux
    Type "help", "copyright", "credits" or "license" for more informatio

Also the following packages are required: <br/>
- python-magic
- selenium
- datetime
- urllib
- json
- PyTorch

All packges except PyTorch are available via `pip` or `anaconda install`
<br />


Installing PyTorch:
<br />
You can follow the instructions provided here: http://pytorch.org/ 
<br />
I installed the GPU-Version using :
</br >
conda install pytorch torchvision cuda80 -c soumith

<br />
## Run the application

Assuming that you already have installed anaconda in Anaconda_path, run the following command:

    ${Anaconda_path}/python RaccoonVsCats.py
<br />
Enjoy!

<br />
Feel Free To contact me for any comments or suggestions.

## TODO List
     TODO: 
     -- Add comments and improve code
     -- remove duplicate images as well as bad samples automatically 
     -- Add TensorBoard with PyTorch  
     -- Add TensorFlow model
     -- Deploy on a web-server 
     

## Use it with any categories.
You can train your custom system by modifying the queries inside script:
    
    queries=['Raccoon','Cat' ]
    Attributes=['running']

 

Disclaimer:
    <br />
    1. Google images are subject to licensing. In case you want to use these images you  should refer to the license of every particular image
    <br />
    2. This tool does not allow you to surpass these licensing options. 
    <br />
    3. You will use this tool only for good purposes.
    <br />
    4.  There is not guarantee that this projects meet your needs, or any guarantee of correctness. 
    <br />

