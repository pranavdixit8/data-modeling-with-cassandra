# Setting up your environment for the project

## Prerequisites
- Cassandra: if not pre-installed, install from  [here](https://cassandra.apache.org/doc/latest/getting_started/installing.html)

## Getting started

#### Clone the repository
```
$ git clone https://github.com/pranavdixit8/data-modeling-with-cassandra.git
```
#### Set up your environement and install all the dependencies
```
$ virtualenv dend-project2
$ source dend-project2/bin/activate
$ pip install -r requirements.txt
```
#### Create the kernel for the virtual environment
```
$ ipython kernel install --user --name dend-project2
```
Note: Use the kernel ***dend-project2*** while using jupyter notebook
## Commands

#### Open the project jupyter notebook
```
$ jupyter notebook data_modeling_cassandra_notebook.ipynb
```