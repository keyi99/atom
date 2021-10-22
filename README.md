# atomcat
This project is created for finding maximum and minimum coordinates, the simple centre of gravity of the coordinates, and printing out which atoms are bonded to which.
## Table of Contents

- Background
- Install
- Usage
- API
- Contributing
- License

## Background

Atomcat is a python program that can use on the coordinate system for proteins such as [PDB files] (https://www.rcsb.org/). Proteins have many atoms, so it's hard for researchers to find or calculate the coordinates for those atoms. A program was started to make as a result of that. In this program, you can input your original files to calculate automatically. 

## Install

This project uses python 3.7.3 on the linux. And it also needs to import sys for System-specific parameters and functions, numpy for Numerical Python, and re for Regular expression operations. Go check them out if you don't have them locally installed.

```python
#!/usr/bin/env python
```

## Usage

In linux, you can change mode to execute this project on the python environment and input your file on the command line:

```
$ chmod +x atomcat.py
$ ./atomcat.py testdata.dat
```

## API

- numpy

```python
import numpy as np
def atomarr(str,float):
    #usage: create arrays and return lists of coodinates for atoms
    #data file: the name and three coordinates of atoms
    atomarr = np.array(coords) 
    print atomarr
    return

    #example: 
    t1 = np.array(coords);
    print t1
    [[40.228,17.831,13.474],[40.761,17.421,12.230]]
```

- system

```python
def finum(str):
    #usage: calculate the number of command line and make sure the number of arguments is two
    #atomcat.py and a data file
    finum = len(sya.argv)
    if(finum != 2):
        print ("Usage: atomcat.py input_file")
    return
```

- regular expression processing
```python
def elements(str):
    #usage: check elements which start with upper letters following by 0 or more letters and then return the list ele containing all matches
    elements = re.findall ("^[A-Z]{1}[a-z]*",s)
    
```

-append

```python
def names(str):
    
##Contributing

This project exists thanks to all the people who contribute.

##License

