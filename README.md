# LinkPrediction_NLP_PW

This task involves investigating the possibility of using **ModernBERT** to perform the task of link prediction in the dataset **FB15K-237**. 

The link prediction task is interpreted as a classification problem, where the model is integrated with a classifier head to discern between valid and corrupted triples. 

The task is performed twice, once with the entities and relations decoded into natural language phrases and another time with the raw entities passed as input of the model, to investigate the importance of pretraing on the outcome of the experiments. 
