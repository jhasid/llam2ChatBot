# llam2ChatBot

## Steps to run using notebook

1. conda create -n venv python=3.8 -y
2. conda activate venv
3. conda env list
4. pip install -r requirements.txt
5. pinecone api_key and index env
6. download model and keep in model folder

## Steps to run using vscode
1. All steps as above
2. create `.env` file in the root directory and add Pine cone credentials as follows

     PINECONE_API_KEY="XXXXXXXXXXXXXXXXXXXXXXXXX"
     PINECONE_API_ENV="XXXXXXXXXXX"
3. create a template.py file for creating folders and files
4. run python template.py     
5. setup.py is required to make src folder as local package (as it is not present in venv )
   all the folders inside src can be used in other file using from src import filename.methodname

