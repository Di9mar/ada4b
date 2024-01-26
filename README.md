# ADA_Final_Project: Detect AI-Generated Text

## Project Overview
This project aims to distinguish between human-generated and AI-generated texts, specifically focusing on texts produced by GPT models. It utilizes DistilBERT for text classification, emphasizing computational efficiency and robust performance.

## Installation
- Clone the repository: `git clone https://github.com/Di9mar/ada4b.git`.
- Ensure Python is installed.
- Configure Google Colab and Google Drive for script execution and data storage.

## Data Setup
Access and prepare datasets from [this Google Drive link](https://drive.google.com/drive/folders/1yMLdiCUE2J_XFjLvO1Fj8G-O-qSRdoSh?usp=sharing). Copy the 'ColabData' folder to your Drive for script compatibility. Essential files:
- wiki_data.csv
- val_dataset.csv
- story_data.csv
- poetry_data.csv
- HC3_data.csv
- essay_data.csv
- combined_abstracts.csv
- 10%_dataset.csv

Note: Additional folders and files will be created or overwritten by the scripts.

## Training and Evaluation
1. **Initial Training**: Run `initial_training_script.py` for the base model.

2. **Further Training**: Use `further_training_script.py`. Customize settings:
   - `trained_model`: Pretrained model for further training.
   - `new_model`: Name for the new model post-training.
   - `data_file`: Dataset for training (from the Drive folder).

3. **Evaluation**: Execute `evaluation_script.py` with adjustments:
   - `current_model`: Models to be evaluated.
   - `data_file`: Dataset for evaluation (from the Drive folder).

Outputs such as models, logs, and metrics are saved in the 'ColabData' folder in Drive.

## Project Link
[GitHub Repository](https://github.com/Di9mar/ada4b.git)
