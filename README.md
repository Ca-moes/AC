## AC

Notebook fica neste repositório e usa-se git como controlo de versões

https://github.com/diogohalmeida/FEUP-AC-PROJ/blob/main/Merging.ipynb 👀

## Instalação ambiente conda/jupyter

Usar [Conda](https://docs.conda.io/en/latest/#) para package management e para Jupyter. 
> The fastest way to obtain conda is to install Miniconda, a mini version of Anaconda that includes only conda and its dependencies. If you prefer to have conda plus over 7,500 open-source packages, install Anaconda.

Daqui escolher qual instalar [FAQ](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html#anaconda-or-miniconda): 
- Anaconda
- Miniconda

E em que sistema Operativo: [Windows](https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html) ou [Linux](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)

### Em Linux 

Após ter tudo instalado (e ter feito `conda update conda`), cria-se um ambiente novo para AC com jupyter lab e a biblioteca pandas:
```bash
conda create -n ac jupyter pandas
```

Ativa-se o ambiente com: `conda activate ac` para trabalhar nesse ambiente e inicia-se o Jupyter Lab com `jupyter lab` para trabalhar no repo