# Liveness-Sample

Steps to run this project:

1. clone the repository: `git clone https://github.com/alex-carneiro/Liveness-Sample.git`
2. enter the project's directory: `cd Liveness-Sample/`
3. install the requirements: `pip install -r requirements.txt`
4. run jupyter notebook: `jupyter-notebook`
5. access the jupyter server in the localhost: `http://localhost:8888/tree`
6. open the notebook file
7. copy a liveness dataset to the project's directory and fix it according to these patterns:

```
dataset/
│
└───train/
|   |
│   └───live/
│   |       image01.jpg
│   |       image02.jpg
│   |       ...
|   |
│   └───spoof/
│           image01.jpg
│           image02.jpg
│           ...
│   
└───test/
    |
    └───live/
    |       image01.jpg
    |       image02.jpg
    |       ...
    |
    └───spoof/
            image01.jpg
            image02.jpg
            ...
```
