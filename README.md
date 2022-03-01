# PYTHON EN LOCAL
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r jupyter/requirements.txt
jupyter notebook --no-browse --NotebookApp.token='' --NotebookApp.password=''
```



# DOCKER
```bash
docker-compose up
```
 In both cases the workspace can be access in localhost:8888