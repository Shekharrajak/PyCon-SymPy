### Install SymPy

We recommend that the attendees install the Anaconda Python distribution which includes SymPy, NumPy, and IPython. Once Anaconda is installed simply type the following in a terminal to install the necessary packages:

```
$ conda install numpy ipython-notebook sympy
```

Other alternative installation instructions can be found here:
[http://docs.sympy.org/dev/install.html](http://docs.sympy.org/dev/install.html)


### Check the installation

short Python program that can be used to verify whether a participants environment is set up correctly.


```
#!/usr/bin/env python

try:
    import sympy
except ImportError:
    print("sympy is required")
else:

    if sympy.__version__ < '1.0':
        print("SymPy version 1.0 or newer is required. You have", sympy.__version__)

    if sympy.__version__ != '1.0':
        print("The stable SymPy version 1.0 is recommended. You have", sympy.__version__)

try:
    import matplotlib
except ImportError:
    print("matplotlib is required for the plotting section of the tutorial")

try:
    import IPython
except ImportError:
    print("IPython notebook is required.")
else:
    if IPython.__version__ < '4.1.2':
        print("The latest version of IPython is recommended. You have", IPython.__version__)

print("""A fortran and/or C compiler is required for the code generation portion
of the tutorial. However, if you do not have one, you should not worry, as it
will not be a large part of the tutorial.""")

```

Same Python program is present in this folder, named `install_check.py`.


### Prerequisite

The tutorial will only assume a basic knowledge of Python. No prior knowledge of SymPy or other Python libraries is required, although it is suggested that attendees be familiar with the jupyter notebook. A mathematical knowledge of calculus is recommended.

**If audience are facing problem in installing the ipython or sympy, they can use online tool [http://live.sympy.org/](http://live.sympy.org/)**


### Github repo Installation :

To get the git repository, use: git clone git://github.com/sympy/sympy.git. This can be run locally using ./bin/isympy. To install globally, follow the instructions in the README file.

And you can also access the git repository on the web: https://github.com/sympy/sympy


