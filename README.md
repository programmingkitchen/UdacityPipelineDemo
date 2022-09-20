
# UdacityPipelineDemo

# flask-ml-service
A sample Flask application to showcase the Azure Pipeline.

## Summary of all changesw

1. Python 3.7 using miniconda

2. Uses this requiements


```
(base) randall@Azure:~/UdacityPipelineDemo$ cat requirements.txt
Flask==2.1.1
pandas==0.24.2
scikit-learn==0.20.3
importlib-metadata==4.11.3
virtualenv==20.14.1
argcomplete==2.0.0
joblib==1.1.0
pylint==2.13.7
pytest==7.1.2
(base) randall@Azure:~/UdacityPipelineDemo$ 
```


3. Changes http to https in the curl link in the script

4. This comment had to be toggled so you do from sklearn for joblib

```
from sklearn.externals import joblib
#import joblib

```

5. Changed the size, but this may not have had an effect.


## Change log

In initial version (incorrect setup) azure-pipelines.yaml added by Azure DevOps when workign through the GUI

9/19/22
Issue with the requirments file.  Need to use older versions.  This was fixed in the project solution code, but not here

```
Flask==1.0.2
pandas==0.24.2.
scikit-learn==1.20.3
importlib-metadata==4.11.3
virtualenv==20.14.1
argcomplete==2.0.0
joblib==1.1.0
pylint==2.13.7
pytest==7.1.2

There is an issue with Python 3.9 which is the only version installed on Azure Cloud Shell.

```

## Environment
Python 3.7

## Orginal location of this code
nd082-Azure-Cloud-DevOps-Starter-Code/C2-AgileDevelopmentwithAzure/azure_pipelines_exercise/starter_files/

