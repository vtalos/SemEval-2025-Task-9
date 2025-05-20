# SemEval 2025 Task 9: The Food Hazard Detection Challenge

The [Food Hazard Detection task](https://food-hazard-detection-semeval-2025.github.io/) evaluates explainable classification systems for titles of food-incident reports collected from the web. These algorithms may help automated crawlers find and extract food issues from web sources like social media in the future. 

The SemEval-Task combines two sub-tasks:

- (ST1) Text classification for food hazard prediction, predicting the type of hazard and product.
- (ST2) Food hazard and product “vector” detection, predicting the exact hazard and product.

The task focuses on detecting the hazard and uses a two-step scoring metric based on the macro F1 score, focusing on the hazard label per sub-task.

The current repository provides a solution for this task using transformer-based models.
