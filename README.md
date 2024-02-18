# chicken_mlops
after witing setup and requirementstxttxt file create conda envorinment
conda create -n chickenml python==3.8 -y
next do pip install -r requirements.txt
create logging file in __init__ in src>cnn>_init__ file
create main.py to and run it to check if log is getting generated
create exception utils in ustils we use files which we commonaly use create common.py in utils

Update config.yaml file it should have create artifacts and source file to download the data
on research create 01_data_ingestion.ipynb file

entity is a retun type of function
to read the yaml file update the constants __init__ file
update the dummy val in parms.yaml

create the data class paths to get the files from config yaml in 01_data_ingestion.ipynb
next create constant in 01_data_ingestion.ipynb to import all from constants __init__ file
import utils common read_yaml,create_directories in 01_data_ingestion.ipynb to import all from constants __init__ file






Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config
Update the components
Update the pipeline
Update the main.py
Update the dvc.yaml