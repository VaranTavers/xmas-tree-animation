# xmas-tree-animation

Some Pluto.jl notebooks to create animations for Matt Parker's XMasTree.

# How to get started?

## I just need the animations

In case you just want the animations that are pre-made you can just copy the CSV files, and you can use them any way you like.

You can open them in a compatible viewer:

* TBD

Or you can run them on an XMasTree (<https://github.com/GSD6338/XmasTree>)

## I want to create new animations                                         
                                                                             
In case you want to create new animations using the code that is provided you will need `julia` <https://julialang.org/> and `Pluto.jl` <https://github.com/fonsp/Pluto.jl>

Installing `Pluto.jl` is easy after installing `julia`, just start `julia` and enter the following command. (you don't have to write `julia>` it's just there to show that you have to type in the command in the julia shell)

```
julia> Using Pkg; Pkg.add("Pluto")
```

After that you can run the notebooks by running the following commands (it is advised to run them in the repo's folder):

```
julia> using Pluto
julia> Pluto.run()
```

After running the second command it should open up a new tab in your browser where you can open the notebooks, and run them.
