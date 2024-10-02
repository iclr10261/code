# This is the Anonymous Code Repository for the ICLR Submission "How much can we Forget about Data Contamination?" 

Here we give a brief overview of the code:

- ```evaluation/```: Contains the code to format benchmark questions, de-duplicate them, and generate the differnt splits that we use for contamination.
- ```llm.c/```: Contains the code to contaminate, train, and evaluate small GPT-3 models.
- ```olmo/```: Contains code to download specific training batches, contaminate them, and insert them back into the the olmo pre-training run. This code depends on https://github.com/allenai/OLMo.
- ```compute_results.ipynb```: Compute accuracies, confidence intervals.
- ```figures.ipynb```: Generate the figures in the paper.
- ```forgetting_curves.ipynb```: Generate the forgetting curves.
