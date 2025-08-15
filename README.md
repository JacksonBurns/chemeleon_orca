# chemeleon_orca
Demo for using ORCA's Python interface with CheMeleon

## Dependencies

Originally developed on Python 3.12, though it should also work on Python 3.11.

`pip install orca-pi 'chemprop>=2.2.1' ipykernel ipywidgets matplotlib`

Make sure you have Open MPI installed, which ORCA requires.
For me on Ubuntu 24, I just had to run `sudo apt install openmpi-bin libopenmpi-dev`.

And of course, install orca: https://www.faccts.de/docs/orca/6.1/tutorials/first_steps/install.html

Note that other QM packages like `pyscf` and `psi4` could also be used here, if one is interested in rewriting some of the provided code (which shouldn't be _too_ hard).

## Running

Simply execute the [`demo.ipynb`](./demo.ipynb) Jupyter notebook using your preferred method (I used VSCode's notebook extension).
