# datafun-07-ml
44608 Week 7 Project: Machine Learning
# Module 7 Project
Scott Williamson - June 10, 2024

## Introduction 
Project utilizing Python and Jupyter Notebooks to explore Machine Learning.

## Project Start-up

-Clone github repository to VS Code

-Add .gitignore and requirements.txt

-Create Virtual Environment
```python
python3 -m venv .venv
source .venv/bin/activate
```

-Install Dependencies and Freeze Requirements
```python
python3 -m pip install --upgrade pip build setuptools wheel 
python3 -m pip install --upgrade ipykernel jupyterlab
python3 -m pip install jupyterlab numpy pandas pyarrow matplotlib seaborn scipy
python3 -m pip install pymongo pyspark tensorflow wordcloud scikit-learn

python3 -m pip freeze > requirements.txt
```

## Git Add/Commit/Push
```python
git add .
git commit -m "...insert commit comment"
git push origin main
```