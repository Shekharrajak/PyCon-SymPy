You can install SymEngine.jl by giving the following command.

```
julia> Pkg.add("SymEngine")
```

Test some code :

```
julia> a=symbols(:a); b=symbols(:b)
b

julia> a,b = symbols("a b")
(a, b)

julia> @vars a b
(a, b)

```
