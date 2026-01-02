# nlp_fact-check

For the classification part, lightweight model was used in this combined, more comprehensive notebook, which can independently run end-to-end and produce the required results from our pipeline. Additionally, a second notebook is provided (NLP_Project_2), which includes a heavier classification model offering improved prediction accuracy. For everything to work correctly:

*   Set the file path for the outputs to be saved and loaded in the beginning of Dataset Processing step
*   During the fine-tuning process at 2.2.1, please paste this as the API key: 3af4026679a5e45628d106493eab99fca2ba1890
*   Put the notebooks and original files (train-claims.json, test-claims-unlabelled.json; dev-claims.json; evidence.json; dev-claims-baseline.json; eval.py) in the the same folder
