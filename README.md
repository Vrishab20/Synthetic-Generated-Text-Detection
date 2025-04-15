 # Assignment 2 – Machine-Generated Text Detection
 Installation
 Before running any part of the assignment, install the required dependencies:
```bash
pip install -r requirements.txt
```

# Assignment Structure
The assignment is divided into two main tasks:
🔹 Task 1: Baseline Models
This task focuses on traditional machine learning models:
1. SVM (Support Vector Machine)
2. Random Forest

The results for these models are saved in:
a. Results_SVM.jsonl
b. Results_Forest.jsonl

🔹 Task 2: Transformer-based Models
This task involves large language models (LLMs):
1. BERT-based classifier
2. LLaMA-based classifier

The results for these models are saved in:
a. Results_Bert.jsonl
b. Results_Llama.jsonl

🔹Evaluation
To evaluate the performance of each model:
Download and set up scorer.py from the official SemEval repository.
Use the following command to evaluate any model's results:
```bash
python scorer.py --gold_file_path=subtaskA_monolingual.jsonl --pred_file_path=Results_<ModelName>.jsonl
```
Replace <ModelName> with:
🔹SVM
🔹Forest
🔹Bert
🔹Llama


