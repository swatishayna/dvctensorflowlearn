DVC - DL - TF - AIOPS demo
commands -
create a new env
conda create --prefix ./env python=3.7 -y
activate new env
source activate ./env
init DVC
git init
dvc init
create empty files -
mkdir -p src/utils config
touch src/__init__.py src/utils/__init__.py param.yaml dvc.yaml config/config.yaml src/stage_01_load_save.py src/utils/all_utils.py setup.py .gitignore
