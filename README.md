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

This project uses python 3.7.3 on the linux. Go check them out if you don't have them locally installed.

```
$ sudo apt-get update
$ sudo apt-get install python3.7.3
```

## Usage

In linux, you can run this code on the login mode: 

```
login as:
Password:
```

Find this project on the directory: /datastore/home/s2173925/intro_prog_pract/pract1, and change to it

You can change mode to execute this project on the python environment and input your file on the command line:

```
$ chmod +x atomcat.py
$ ./atomcat.py testdata.dat
```

## API
- numpy

```python
import numpy as np
```

- System-specific parameters and functions

```python
import sys
```

- Regular expression operations

```python
import re
```

## Contributing

This project exists thanks to all the people who contribute.

## License

