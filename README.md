## PyCon-SymPy-SymEngine

PyCon India -  SymPy & SymEngine

* Proposal Link: [SymPy, Symengine and it's wrapper for different programming languages as computer aided algebra system (CAS)](https://in.pycon.org/cfp/2017/proposals/sympy-symengine-and-its-wrapper-for-different-programming-languages-as-computer-aided-algebra-system-cas~eXnob/)

* Website Link: [Pycon_india_2017](https://shekharrajak.github.io/PyCon-SymPy-SymEngine/)

* [In sympy/wiki](https://github.com/sympy/sympy/wiki/PyCon-India-2017-Proposal) 

## About SymPy & SymEngine

SymPy is a pure Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible in order to be comprehensible and easily extensible. SymPy is written entirely in Python and does not require any external library.

SymEngine is a standalone fast C++ symbolic manipulation library. Optional thin wrappers allow usage of the library from other languages.

## Proposal 

**SymPy** is a pure Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible in order to be comprehensible and easily extensible. SymPy is written entirely in Python and does not require any external libraries.

This tutorial is intended to cover the basics as well as touch on more advanced topics. We will start by showing how to install and configure this Python module. Then we will proceed to the basics of constructing and manipulating mathematical expressions in SymPy. We will also discuss the most common issues and differences from other computer algebra systems, and how to deal with them. In the remaining part of this tutorial we will show how to solve mathematical problems with SymPy.

This knowledge should be enough for attendees to start using SymPy for solving mathematical problems and hacking SymPy's internals (though hacking core modules may require additional expertise).

**SymEngine** is a standalone fast C++ symbolic manipulation library. Optional thin wrappers allow usage of the library from other languages (Python, Ruby, Julia, Haskell).

The workshop will also include a hands-on introduction to SymEngine in Python for the advantages of speed while using SymPy. This section would focus heavily on SymEngine's Python wrapper called SymEngine.py, and the various methodologies employed by it, the use of Cython, an account of the modules currently supporting the use of SymEngine, the subsequent impact on performance and the major projects using SymEngine. In addition to the above, there will also be a light introduction towards installation and usage of SymEngine library in Ruby, Haskell and Julia, through their respective wrappers.

We expect attendees of this tutorial to have basic knowledge of Python, C++, Ruby, Julia and mathematics. However, many more advanced topics for SymPy will be explained during presentation and basic examples for SymEngine wrappers. No prior knowledge of SymPy or other Python libraries is required, although it is suggested that attendees be familiar with the IPython notebook


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

The website for the workshop at PyCon India 2017 is [here](https://shekharrajak.github.io/PyCon-SymPy-SymEngine/)
(You can find the introduction slides, the sphinx tutorial, and The exercises in form of IPython notebooks in the website navbar).

Note: that the notebooks are hosted statically, you can download from the [repo](https://github.com/Shekharrajak/PyCon-SymPy-SymEngine) and run locally to have an interactive session.

SymPy India developers will be conducting the workshop:

* [Amit Kumar](https://github.com/aktech), Core Developer & GSoC-cer at SymPy
* [Shekhar Prasad Rajak](https://github.com/Shekharrajak) : NIT Warangal | Core Developer at SymPy GSoC 2016 | Solvers, Sets <br>
* [Shikhar Jaiswal](https://github.com/ShikharJ) : IIT Patna | Student Developer at SymPy GSoC 2017 | SymPy - SymEngine Integration and Python Wrappers <br>
* [Ranjith Kumar](https://github.com/ranjithkumar007) : IIT Kharagpur | Student Developer at SymPy GSoC 2017 | Solvers and Sets in SymEngine <br>
