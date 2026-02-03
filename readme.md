## Python for Data Analysis, 3E

- [Book](https://wesmckinney.com/book/)
- [Book Code](https://github.com/wesm/pydata-book)

## Libraries 

- [NumPy documentation](https://numpy.org/doc/stable/)
- [Pandas Getting started](https://pandas.pydata.org/getting_started.html)
- [Matplotlib: Visualization with Python](https://matplotlib.org/)
- [Matplotlib Getting started](https://matplotlib.org/stable/users/getting_started/)

## Installing Python 3.10

- [Python 3.10.0](https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe)

- [Python 3.10.11](https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe)

- or 
```
winget install -e --id Python.Python.3.10.11
```
1. First check if the Python launcher exists

```
py --version

```

- If you get a version (ex: Python 3.10.x)

- Then pip is there — just call it through Python:

```
py -m pip --version
py -m pip install --upgrade pip

```

- From now on, use:

```
py -m pip install <package>
```

2.  Don’t use pip directly (best practice)

- Even after install, I recommend you run pip like this to avoid PATH issues:

```
python -m pip install numpy pandas jupyter matplotlib
```
- or use

```
py -m pip ...
```


## PIP

- In the cmd shell install the ipython

```
pip install ipython
```

- To install the numpy
  
```
pip install numpy
```

## To activate the virtual environment

- at the root folder (my-code)

```
mkdir test-app

cd test-app

python -m venv myenv

.\myenv\Scripts\activate

```

- if you have issue with activating the environment 
  
![issue](/Assets/script-execution-issue.png)


```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

- if prompted say yes

```
.\myenv\Scripts\activate
```

- verify the venv is activated

![active-env](/Assets/activated-venv.png)

- You can import the needed packages and libraries

- create a test.ipynb file 

- Test Feb 







Feb 3rd 2026
