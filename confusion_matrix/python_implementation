import numpy as np
from sklearn.metrics import confusion_matrix
import seaborn as sns
import matplotlib.pyplot as plt

#Air Quality Alert Prediction
#'actual' represents the true air quality condition
#'predicted' represents the model's predicted condition
actual = np.array(['Safe','Unsafe','Safe','Unsafe','Unsafe','Safe','Safe','Unsafe','Safe','Unsafe'])
predicted = np.array(['Safe','Safe','Safe','Unsafe','Unsafe','Safe','Unsafe','Unsafe','Safe','Unsafe'])

#Generate the confusion matrix
cm=confusion_matrix(actual,predicted)

#Visualizing the Confusion Matrix
sns.heatmap(cm,annot=True,cmap='Blues',xticklabels=['Safe','Unsafe'],yticklabels=['Safe','Unsafe'])
#annot=True always to display numerical values inside each cell in the heatmap

#Label the axes
plt.ylabel('Actual Air Quality',fontsize=13)
plt.xlabel('Predicted Air Quality',fontsize=13)
#Adding title to the visualization
plt.title('Confusion Matrix – Air Quality Alert Prediction',fontsize=17)

#Display the heatmap
plt.show()
