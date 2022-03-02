# Local Installation (Python and Pip)
```bash
#Create Virtual Environment
python3 -m venv .venv
#Activate Virtual Environment
source .venv/bin/activate
#Install libraries required for the project
python -m pip install -r jupyter/requirements.txt
#Run Jupyter Notebook
jupyter notebook --no-browse --NotebookApp.token='' --NotebookApp.password=''
```



# VM (Docker)
```bash
docker-compose up
```
#### In both cases, the workspace is accessible through [localhost:8888](http://localhost:8888).
