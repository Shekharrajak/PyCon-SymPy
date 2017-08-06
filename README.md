## PyCon-SymPy-SymEngine

PyCon India -  SymPy & SymEngine

* Proposal Link: [Symbolic computation with Python](#)

* Website Link: [pycon_2017](https://shekharrajak.github.io/PyCon-SymPy-SymEngine/)

## About SymPy & SymEngine

SymPy is a pure Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible in order to be comprehensible and easily extensible. SymPy is written entirely in Python and does not require any external library.

SymEngine is a standalone fast C++ symbolic manipulation library. Optional thin wrappers allow usage of the library from other languages

## SymPy & SymEngine Tutorial for PyCon India 2017

This is the tutorial that SymPy developers will be giving at PyCon India 2017 for SymPy.
In this tutorial we will introduce attendees to SymPy, a computer aided algebra system (CAS) written in Python, and SymEngine, a CAS written in C++. We will show basics of constructing and manipulating mathematical expressions in SymPy, the most common issues and differences from other computer algebra systems, and how to deal with them. In the last part of this tutorial, we will show how to solve practical problems with SymPy. This will include showing how to interface SymPy with popular numeric libraries like NumPy.

The workshop will also include a hands-on introduction to SymEngine in Python for the advantages of speed while using SymPy. This section would focus heavily on SymEngine's Python wrapper called SymEngine.py, and the various methodologies employed by it, the use of Cython, an account of the modules currently supporting the use of SymEngine, the subsequent impact on performance and the major projects using SymEngine. In addition to the above, there will also be a light introduction towards installation and usage of SymEngine library in Ruby, Haskell and Julia, through their respective wrappers.

Attendees will take home an introductory level understanding of SymPy. This knowledge should be enough for attendees to start using SymPy for solving mathematical problems and hacking SymPy's internals (though hacking core modules may require additional expertise).


## Speaker Info

TODO: Add names

SymPy India developers will be conducting the workshop:

* [name](https://github.com/name) : Desc | Core Developer at SymPy GSoC Year | Module


## Proposal (will modify it and use it for pycon): 

In this tutorial we will introduce attendees to SymPy, a computer aided algebra system (CAS) written in Python. We will show basics of constructing and manipulating mathematical expressions in SymPy, the most common issues and differences from other computer algebra systems, and how to deal with them. We will mostly show how to solve practical problems with SymPy and SymEngine. This will include showing how to interface SymPy with popular numeric libraries like NumPy.

Attendees will take home an introductory level understanding of SymPy. This knowledge should be enough for attendees to start using SymPy for solving mathematical problems and hacking SymPy's internals (though hacking core modules may require additional expertise).

SymPy is a pure Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible in order to be comprehensible and easily extensible. SymPy is written entirely in Python and does not require any external libraries. The tutorial will cover the following topics and more.


    Introduction
        What is Symbolic Computation?
        A More Interesting Example
       The Power of Symbolic Computation
       Why SymPy?
    Gotchas
        Symbols
        Equals signs
        Two Final Notes: ^ and /
    Basic Operations
        Substitution
        Converting Strings to SymPy Expressions
        evalf
        lambdify
        Printing
        Printers
        Setting up Pretty Printing
        Printing Functions
        Simplification
        simplify
        Polynomial/Rational Function Simplification
        Trigonometric Simplification
        Powers
        Exponentials and logarithms
        Special Functions
    Calculus
        Derivatives
        Integrals
        Limits
        Series Expansion
        Finite differences
        Solvers
       A Note about Equations
       Solving Equations Algebraically
       Solving Differential Equations
    Matrices
       Basic Operations
       Basic Methods
       Matrix Constructors
       Advanced Methods
    Advanced Expression Manipulation
       Understanding Expression Trees
       Recursing through an Expression Tree


The tutorial will only assume a basic knowledge of Python and C++. No prior knowledge of SymPy or other Python libraries is required, although it is suggested that attendees be familiar with the IPython notebook. A mathematical knowledge of calculus is recommended.

We recommend that the attendees install the Anaconda Python distribution which includes SymPy, NumPy, and IPython. Once Anaconda is installed simply type the following in a terminal to install the necessary packages:

`$ conda install numpy ipython-notebook sympy`

Other alternative installation instructions can be found here: http://docs.sympy.org/dev/install.html

SymEngine and its Python wrapper can be installed directly through:

`$ conda install -c conda-forge python-symengine`

Other alternative installation instructions can be found at:

- `https://github.com/symengine/symengine/wiki/Building-SymEngine`
- `https://github.com/symengine/symengine.py/`
- `https://github.com/symengine/symengine.rb/`
- `https://github.com/symengine/symengine.jl/`
- `https://github.com/symengine/symengine.hs/`

SymPy team has developed and delivered many talks and tutorials at SciPy and other conferences. 
We are constantly building on new content and improving the present at the same time. 
The website for the workshop at PyCon India 2015 is here. 
You can find the introduction slides here, the sphinx tutorial here and the exercises in form of IPython notebooks here. 
Note: that the notebooks are hosted statically, you can download from here and run locally to have an interactive session.

SymPy India developers will be conducting the workshop: 

* [Shekhar Prasad Rajak](https://github.com/Shekharrajak) : NIT Warangal | Core Developer at SymPy GSoC 2016 | Solvers, Sets <br>
* [Shikhar Jaiswal](https://github.com/ShikharJ) : IIT Patna | Student Developer at SymPy GSoC 2017 | SymPy - SymEngine Integration and Python Wrappers <br>
* [Ranjith Kumar](https://github.com/ranjithkumar007) : IIT Kharagpur | Student Developer at SymPy GSoC 2017 | Solvers and Sets in SymEngine <br>

TODO: add name here
