# Multiple Dispatch

A quick exploration of the aspects of Julia I like

Interested to give Julia a quick try? Here are some helpful info =)

## Install

Some options:-

1. Why install? Try it out in browser at [JuliaBox](https://www.juliabox.com) =P
1. Install [JuliaPro](https://juliacomputing.com/products/juliapro.html), batteries-included
1. On mac, `brew cask install julia`
1. Download and install using [Julia installer](https://julialang.org/downloads/)
1. Build from [source](https://github.com/JuliaLang/julia)


## Run

1. Make the Julia binary available in PATH, and run `julia` in cmd
1. Install Jupyter Notebook, then add the [IJulia.jl](https://github.com/JuliaLang/IJulia.jl) package to have the Julia kernel available to Jupyter Notebook
1. Run Juno in Atom / VS Code (takes some effort to setup, but can do fanciful things like code snippet evaluation in IDE)


## Add packages

For example, say we want to use the [PyCall.jl](https://github.com/JuliaPy/PyCall.jl) package to call Python functions from the Julia language.

Run the following once inside Julia to grab the master branch of the package

```julia
Pkg.add("PyCall")  #note that .jl should not be included
```

Put the following line in a source file to use the `PyCall` package

```julia
using PyCall
```


## Code files in this repo

The `.ipynb` are Jupyter Notebooks. They can be viewed in GitHub directly, but to run it, there need to be a Jupyter environment. From scratch, the easiest way is to create a JuliaBox account and open the files from there.
