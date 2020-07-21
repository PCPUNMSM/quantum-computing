# Quantum Computing

These materials were written by Martin Vuelta ([@zodiacfireworks][zodiacfireworks]) and Ricardo Quispe ([@RcrdPhysics][RcrdPhysics]) as part of the [Qiskit Global Summer School][1] by IBM, with the support of [SoftButterfly][2].

## How to use

### Tools

For active develpment we are using

* Python 3.8
* [Pyenv][3]
* [Poetry][4]

### Install

- Clone the repository

```bash
git clone git@github.com:PCPUNMSM/quantum-computing.git
cd quantum-computing
```

- Install dependencies

```bash
poetry install
poetry run jupyter labextension install \
    @jupyter-widgets/jupyterlab-manager \
    @jupyterlab/debugger \
    @jupyterlab/git \
    @jupyterlab/toc \
    @krassowski/jupyterlab_go_to_definition \
    @lckr/jupyterlab_variableinspector \
    @ryantam626/jupyterlab_code_formatter \
    nbdime-jupyterlab
```

- Enjoy the notebooks :D

```bash
poetry run jupyter lab
```

## I only want to see the notebooks in action!

Check them [here][5]!

If you got a 404 please add `?flush_cache=true` at the end of the URL or drop us a line! :D

[1]: https://qiskit.org/events/summer-school/
[2]: http://softbutterfly.io/
[3]: https://github.com/pyenv/pyenv
[4]: https://python-poetry.org/
[5]: https://nbviewer.jupyter.org/github/PCPUNMSM/quantum-computing/tree/master/notebooks?flush_cache=true
[RcrdPhysics]: https://github.com/RcrdPhysics
[zodiacfireworks]: https://github.com/zodiacfireworks
