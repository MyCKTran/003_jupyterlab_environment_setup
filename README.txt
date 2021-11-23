This document is used for installing jupiter lab with conda environment
Note: 
     + User should deeply understand conda environment by check at 'https://github.com/MyCKTran/01_conda_environment_setup'
     + Command line in this document is always in double quotes ("")
     + Name file/object mentioned is in single quote ('')

Step 1: Create a conda environment with the command line: "conda create --name py36 python=3.6" 

Step 2: Activate the conda environment by the command line:  "conda activate py36"

Step 3: Install jupiter-lab with the command line: "conda install -c conda-forge jupyterlab"
        After the install process finished, use the command line:  "which jupyter" to check whether 'jupyterlab' was installed.
    
Step 4: Open jupyter-lab by the command line: "jupyter-lab". Then, a web interfance will automatically opened. 
        Next, user can choose 'Notebook' or 'Console' to write python code
        The jupyter-lab file after saving is with the file extension of 'ipynb'

* Some popular coding editors: Vim, Jupyter-Notebook/lab, PyCham, Atom, etc. 
* Convert <file>.ipynb to <file>.py by the command line:   "ipython nbconvert <file>.ipynb --to script". Then a <file>.py is generated. Run this file with command line on the terminal: "python <file>.py"
* If we want to run on <file>.jpynb, we run the command line: "ipython". Then run the command line:  "run <file>.ipynb" (This is not recommend)

