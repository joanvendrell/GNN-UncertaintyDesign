# MAE 285: Uncertainty Design

<p align="center">
  <img src="./assets/peteranteater.png" width="250" title="Peter the Anteater">
  <img src="./assets/ucisamueli.png" width="200" alt="UCI">
</p>

This repository is an implementation of a Graph Neural Network for the course 285 from the Mechanical and Arospace Department of the University of California Irvine.
In this porject, we implemented a [Learning Mesh-Based Simulation with Graph Networks](https://arxiv.org/abs/2010.03409) for computing torsion and deformation over
distinct beams profiles.

<p align="center">
<img width="420" alt="Captura de pantalla 2024-12-10 a les 1 46 25 p  m" src="https://github.com/user-attachments/assets/1992f9a4-7431-4af0-a5ad-38c05f1964fc">
<img width="419" alt="Captura de pantalla 2024-12-10 a les 1 46 37 p  m" src="https://github.com/user-attachments/assets/cc0df223-8cdd-4e34-8850-429d5fee0c14">
</p>

%## Setup
%> Ubuntu based
%- `python3.10 -m venv mae285_env`
%- `source ./mae285_env/bin/activate`
%- `python3.10 -m pip install -r requirements.txt`
%- `ipython kernel install --user --name=mae285_env`
%- `jupyter lab`
%> Windows based
%- `py -3.10 -m venv mae285_env`
%- `./mae285_env/Scripts/activate`
%- `python -m pip install -r requirements.txt`
%- `ipython kernel install --user --name=mae285_env`
%- `jupyter lab`
%## Git authentication
%- `git config --local user.name "Your Name"`
%- `git config --local user.email "Your Email"`
%- `git remote set-url origin https://username:token@github.com/username/repository.git`
%## Join splitted files
%> Ubuntu based
%### Split
%`split -b 99M ./T.json ./splitted/T.json.`
%### Join
%`cat ./splitted/T.json.* > ./T.json`
