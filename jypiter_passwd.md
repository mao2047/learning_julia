## to set jupiter password in linux (jan/2022) for Julia

1. check to see if you have a jupyter config file

On linux would be in ~/.jupyter
if it's not there then generate it.

Find where Jupyter is intalled: **Pkg.dir("Conda"). For me, it was isntalled in ~/.julia/conda 

and then find the Jupyter subdirectory to generate a config file:

~/.julia/conda/3/bin/jupyter --generate-config

2. Generate password

run: ~/.julia/conda/3/bin/jupyter notebook password

then type in a new password

actualizado de [aquí](https://discourse.julialang.org/t/ijulia-password-token-requirement/4974)
