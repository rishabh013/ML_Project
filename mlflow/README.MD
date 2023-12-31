### Created new environment
---
conda create -p mlenv python==3.8     OR  python3 -m venv mlenv
---
### Activate the environment
---
conda activate mlenv/                 OR  . mlenv/bin/activate
---
### Instal all necessary liberies
---
pip install -r requirements.txt
---

## create new file command
-----
touch run.py
-----
### Instal all necessary liberies
---
pip install -r requirements_mlflow.txt
---

1.  01_first_trail.py   ## just for trial this code
''' After run first_trail.py we get one folder mlruns in which we get the information/tracking about the the our models''' 
'''After run the above the code we can see in online plateform as well through the mlflow ui'''
### watch online tracking ml parameter
----
mlflow ui
----

2. 02_basic_ml_model.py   ''' this is the entire code of mlflow'''
3. text.ipynb             ''' This is a notebook to test the model '''
3. 03_test.py             ''' testing how argument works  ''' 
4. 04_run.py              ''' it is use for differnt-different experiment in ml flow for various estimator'''


