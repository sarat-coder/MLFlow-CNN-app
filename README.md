# MLflow-Project-template
# MLflow-Project-template
## STEP 01- Create a repository by using template repository
## STEP 02- Clone the new repository
## Open the project in vs code.
## open terminal in bash mode
## activate base env by using 
...bash
source activate base
...

## STEP 03- Create a conda environment after opening the repository in VSCODE
'''bash
conda create --prefix ./env python=3.7 -y
'''
Or
'''bash
conda activate ./env
'''
OR
source activate ./env
## STEP 04- install the requirements
'''bash
pip install -r requirements.txt
...
## STEP 05- Create conda.yaml file
'''bash
conda env export > conda.yaml
...
## STEP 06- commit and push the changes to the remote repository