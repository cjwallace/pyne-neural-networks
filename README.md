# Neural Networks in Python

Hey! Welcome to a silly little talk about neural networks. Everything you need
to participate fully should\* be here (says Chris with trepidation).

## Installation.

1. First, there was python. I recommend the
   [Anaconda](https://www.continuum.io/downloads)
   distribution.
   This talk is written for python 3.5+.

2. Then, you need an environment. If you're using conda to manage environments,
   you can clone this repo and run:
   ```bash
   conda env create -f pyne-nn.yml
   source activate pyne-nn
   ```
   This should create and activate an environment with the appropriate
   packages.

   Alternatively, use whatever environment manager you like, and install the
   necessary packages with pip via:
   ```bash
   pip install -r reqs.txt
   ```

3. Finally, there is jupyter. If you have the environment set up right, run
   ```bash
   jupyter notebook
   ```
   from the command line. This will open up a browser. Open the file
   `Codealong Neural Networks.ipynb` and try running the import cell by
   clicking on it and pressing `Shift+Enter`. If everything worked, you're good
   to go!

You won't actually be able to run the presentation as a presentation because
reasons, but you can peak ahead in the notebook.

Trump data credit: https://github.com/ryanmcdermott/trump-speeches.

 \* Works On My Machine (TM), Your Mileage May Vary, etc.
