# Background
Lung cancer is one of the leading causes of cancer-related mortalities worlwide.Individuals across the socio-economic strata may be exposed to risk factors. Putative risk factors of lung cancer include smoking, exposure to environmental pollution etc. However, it is important for us to identify key features (risk factors) with the most accurate effect{s} on lung cancer etiology.
# Rationale
This project will develop a predictive model for lung cancer risk assessment using a comprehensive dataset of lung cancer outcomes.
# Features
1. Gender Influence: To what extent does gender impact the likelihood of developing lung cancer, and are there notable gender-based disparities? 
  
2. Age-Related Risk: How does age factor into the risk of lung cancer, and is there a particular age group more vulnerable? (continuous variable)
  
3. Smoking: How does a history of smoking relate to the risk of lung cancer, and is there a straightforward connection? 
   
4. Yellow Fingers: Does the presence of yellow fingers, possibly due to nicotine staining, correlate with an elevated risk of lung cancer? 

5. Chronic Lung Diseases: Are individuals with chronic diseases at a higher risk of developing lung cancer?

6. Fatigue and Risk: Does chronic fatigue or tiredness play a role in lung cancer risk?

7. Allergies and Susceptibility: Is there a correlation between allergies and an increased risk of lung cancer?

8. Wheezing Connection: How strong is the association between wheezing and the likelihood of developing lung cancer?

9. Alcohol Impact: Do patterns of alcohol consumption influence lung cancer risk?

10. Coughing of blood: Is there a significant relationship between chronic coughing (of blood) and lung cancer risk?

11. Respiratory and Swallowing Factors: "How do symptoms like shortness of breath and difficulty in swallowing relate to the risk of lung cancer?"

12. Shortness of breath 

13. Air Pollution               

14. OccuPational Hazards        

15. Genetic Risk                

16. Balanced Diet               

17. Obesity                     

18. Passive Smoker              

19. Chest Pain                  

20. Weight Loss                

21. Frequent Cold              

22. Snoring
    
23. Dry cough                

# Dataset
"/kaggle/input/cancer-patients-and-air-pollution-a-new-link/cancer patient data sets.csv"

# Steps
<img width="923" alt="image" src="https://github.com/oyebolakolapo/Lung_cancer_prediction/assets/40770957/39faba85-fc53-45b1-945d-1f4de0cbbda8">

# Result interpretation
The feature importance results provide insight into which features are most influential in predicting lung cancer using our Random Forest Model. The importance of a feature is calculated based on how much the tree nodes that use that feature reduce impurity across all trees in the forest.

The key findings show that coughing of blood is the most important feature in lung cancer followed by passive smoking, obesity and wheezing.
These results, however, should be interpreted with caution. 

The importance of a feature in a Random Forest model doesn't necessarily mean a casual relationship, and it is specific to this model and this dataset. Other models might find different results. Additionally, low importance doesn't mean that the feature is unimportant for predicting lung cancer in general, it may just mean that the feature is not useful in the presence of the other features. A thorough feature analysis should be considered for a better understanding of the contribution of each feature in the prediction.

