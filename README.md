# RWTH CSME Bonus Assigment

### [Bonus Assigment 1 PDF](./CSME2-WS2122-BonusPointAssignment1-1.pdf)
### [Notebook link](./Notebooks/CSME2-WS2122-BonusPointAssignment1.ipynb)
### Status:
- [x] A1
- [x] A2
- [x] A3
- [x] A4
- [ ] A5
- [ ] B1
- [ ] B2
- [ ] B3
- [ ] C1
- [ ] C2
- [ ] C3
- [ ] C4 (Optional)

<br>

To mangage and uniform the dependencies, I recommend to use conda environment for the project.
To install Anaconda you can following [this instruction](https://docs.anaconda.com/anaconda/install/index.html), or Miniconda (minimal installller of Anaconda) following [this instruction](https://docs.conda.io/en/latest/miniconda.html#).

### Setting up the environment
```bash
$ conda env create -f environment.yml
$ conda activate csme_rwth
```

### Check Scikit-learn, Numpy and Python version
```bash
$ python dep_ver.py
```

Running the above script should return:

```console
Numpy version:  1.21.4
Scikit-learn version:  1.0.1
Python version:  3.7.12
Matplotlib version:  3.5.0
```

### Running assignment with Jupyterlab
```console
$ jupyter-lab Notebooks/
```

