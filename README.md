## End To End ML Project

### created a environment
```
conda create -p venv python==3.8

conda activate venv/
```
### Install all necessary libraries
```
pip install -r requirements.txt

```
### run setup.py 
```
python setup.py install 
```
### Notes

IN setup.py when there are any major updates in the code we update versions
IN require_packages which lib to install
A function to read from requirements.txt

-e . setup.py initiated

## The src folder contains entire life cycle of the ML project
why __init__.py is used ?
Its used so that the packages or contents os the src folder can be reused by some package (interconnection)

while the setup.py is used to create the over all package   
utils.py contiains the common functionalities for the project
in every folder we have to create __init__.py so that its content can be imported elsewhere 