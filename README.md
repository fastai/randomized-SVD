This is the demo for [my PyBay 2017 talk](http://www.pybay.com/speaker/rachel-thomas/).  If you are not comfortable setting up the demo or unable to do so, you will still get a lot out of the session.

I recommend downloading [Anaconda](https://www.continuum.io/downloads), which contains the main Python scientific libraries.  Alternately, you can create a virtual environment and install the necessary requirements: 

    virtualenv env
    source env/bin/activate
    pip install -r requirements.txt
    
To start the jupyter notebook from the command line:

    jupyter notebook

## Data Sources

### Part 1: Word Embeddings

The dataset of word embeddings is available at http://files.fast.ai/models/glove/6B.100d.tgz
To download and unzip the files from the command line, you can run:

    wget http://files.fast.ai/models/glove_50_glove_100.tgz 
    tar xvzf glove_50_glove_100.tgz
    
### Part 2: Background Removal

Download the real video 003 and 008 datasets from [BMC 2012 Background Models Challenge Dataset](http://bmc.iut-auvergne.com/?page_id=24)
