# Uncertainty Design MAE 285

<p align="center">
  <img src="./assets/peteranteater.png" width="250" title="Peter the Anteater">
  <img src="./assets/ucisamueli.png" width="200" alt="UCI">
</p>

## Setup

> Ubuntu based

- `python3.10 -m venv mae285_env`
- `source ./mae285_env/bin/activate`
- `python3.10 -m pip install -r requirements.txt`
- `ipython kernel install --user --name=mae285_env`
- `jupyter lab`

> Windows based

- `py -3.10 -m venv mae285_env`
- `./mae285_env/Scripts/activate`
- `python -m pip install -r requirements.txt`
- `ipython kernel install --user --name=mae285_env`
- `jupyter lab`

## Git authentication

- `git config --local user.name "Your Name"`
- `git config --local user.email "Your Email"`
- `git remote set-url origin https://username:token@github.com/username/repository.git`

## Join splitted files

> Ubuntu based

### Split

`split -b 99M ./T.json ./splitted/T.json.`

### Join

`cat ./splitted/T.json.* > ./T.json`

## References

- https://arxiv.org/abs/2010.03409