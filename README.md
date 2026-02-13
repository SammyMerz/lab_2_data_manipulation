# lab-02-data manipulation

Setting up our environment for INST447. This assignment contains seven files:

1. [README.md](./README.md) -- _This file_. The instructions you are reading.
2. [lab-02-warmup.ipynb](./lab-02-warmup.ipynb) -- Jupyter notebook with the Lab 02 warmup exercises.
3. [lab-02-main.ipynb](./lab-02-main.ipynb) -- Jupyter notebook with the Lab 02 main assignment.
4. [planets.csv](./planets.csv) -- Dataset used in the lab assignment.
5. [WeatherTrips.csv](./WeatherTrips.csv) -- Additional dataset for lab exercises.
6. [products.csv](./products.csv) -- Additional dataset for lab exercises.
7. [environment.yml](./environment.yml) -- Environment file for BYO coding environments. If you are using the recommended coding environment, you may ignore this file.

# What you need to do

1. Complete and submit `lab-02-warmup.ipynb` in class
2. Complete `lab-02-main.ipynb` afterwards
3. Follow the instructions in each notebook
4. Write your code in the designated answer cells (marked with `...`)
5. Run the submission cells at the end to generate ZIP files
6. Upload the ZIP files to ELMS/Gradescope

# For BYO python only: setting up the virtual environment

__NOTE:__ *You may ignore this section if you are using the recommended Python
environment*.

If you are using your own coding environment (BYO method), you may use the provided environment file to set up a virtual environment. 

To create the virtual environment, open a terminal and run:

```shell
conda env create -f environment.yml
```

To activate the it, run:

```shell
conda activate lab02
```

Then in the same terminal, you can run:

```
jupyter lab
```

And then open the notebook file.
