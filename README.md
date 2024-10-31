# heartattackprediction
Results and Best Model
Based on the results presented:

- Logistic Regression with SMOTE performed well, achieving an accuracy of 73% and significantly improving the recall for the minority class (heart disease) from 7% to 78%.
  
- Decision Tree showed good overall accuracy (85%) but struggled with precision and recall for the minority class.
  
- Random Forest achieved the best overall performance with:
      - Accuracy: 88.37%
      - Precision: 30.25%
      - Recall: 18.20%
      - F1 Score: 22.73%
      - ROC-AUC: 0.7714
The Random Forest model appears to be the best choice for this problem because:
      - It achieved the highest overall accuracy.
      - It provided a better balance between precision and recall for the minority class compared to other models.
      - It had the highest ROC-AUC score, indicating better discrimination between classes.

However, it's worth noting that there's still room for improvement, particularly in the recall for the minority class. Further tuning of the Random Forest model or exploring other advanced techniques like Gradient Boosting might yield even better results
