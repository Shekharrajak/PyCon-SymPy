### Pip

See License section for information about wheels

    pip install symengine --user

### Ubuntu package manager

    add-apt-repository ppa:symengine/ppa
    apt-get update
    apt-get install python-symengine        # or python3-symengine if using python3

### Conda package manager

    conda install python-symengine -c symengine -c conda-forge

### Build from source

Install prerequisites.

    CMake       >= 2.8.7
    Python2     >= 2.7      or Python3 >= 3.3
    Cython      >= 0.19.1
    SymEngine   >= 0.2.0

For SymEngine, only a specific commit/tag (see symengine_version.txt) is supported.
Latest git master branch may not work as there may be breaking changes in SymEngine.

Python wrappers can be installed by,

    python setup.py install

Additional options to setup.py are

    python setup.py install build_ext
        --symengine-dir=/path/to/symengine/install/dir          # Path to SymEngine install directory or build directory
        --compiler=mingw32|msvc|cygwin                          # Select the compiler for Windows
        --generator=cmake-generator                             # CMake Generator
        --build-type=Release|Debug                              # Set build-type for multi-configuration generators like MSVC
        --define="var1=value1;var2=value2"                      # Give options to CMake
        --inplace                                               # Build the extension in source tree

Standard options to setup.py like `--user`, `--prefix` can be used to
configure install location. NumPy is used if found by default, if you wish
to make your choice of NumPy use explicit: then add
e.g. ``WITH_NUMPY=False`` to ``--define``.

Use SymEngine from Python as follows:

    >>> from symengine import var
    >>> var("x y z")
    (x, y, z)
    >>> e = (x+y+z)**2
    >>> e.expand()
    2*x*y + 2*x*z + 2*y*z + x**2 + y**2 + z**2

You can read Python tests in `symengine/tests` to see what features are
implemented.
