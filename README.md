# Censorpic experiment

Information 
This script (main.py) assesses the quality of our tensorflow lite model for nudity detection. This outputs a CSV file with the true class which is defined by you, along with our prediction of that class. The file does not save, display or send any images anywhere.

The user will need to have python installed, download the required libraries, and download the files in this github.  

Before running, the following arugments have to be specified:
--model_path "path/to/tflite/model"
--nude_dataset_path "path/to/folder/with/nude/images"
--non_nude_dataset_path "path/to/folder/with/non_nude/images"
--output_path "path/where/output/is to be produces"

example:
python main.py --model_path "C:\tf_lite_model.tflite" --nude_dataset_path "C:\images\nude" --non_nude_dataset_path "C:\images\non_nude" --output_path "C:\results"


