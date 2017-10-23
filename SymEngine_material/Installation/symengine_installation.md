#### Ubuntu package manager

```
add-apt-repository ppa:symengine/ppa
apt-get update
apt-get install libsymengine-dev
```

#### Conda package manager

```
conda install symengine -c symengine -c conda-forge
```

#### Homebrew pacakge manager

```
brew install homebrew/science/symengine
```

#### Building from source

Install prerequisites. For Debian based systems (Ubuntu etc.):

```
apt-get install cmake libgmp-dev
```

For RPM based systems (Fedora etc.):

```
yum install cmake gmp-devel
````

Install SymEngine:

```
cmake .
make
make install
```

This will configure and build SymEngine in the default Release mode with all code and compiler optimizations on and then install it on your system.

Run tests:

`ctest`

