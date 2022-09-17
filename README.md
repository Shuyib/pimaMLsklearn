# pimaMLsklearn
Using various supervised learning estimators in Sci-Kit Learn to get the best prediction accuracy if possible for the pima indians dataset. 

Begin by reviewing the package requirements in requirements.txt

Train - test split accuracy with SVM(Support Vector Classifier) 0.77

Train - test split accuracy with Random Forest Classifier 0.76

Accuracy mean cross-validation score: 0.83 scoring "roc_auc" for Random forest Classifier
Accuracy mean cross-validation score: 0.69 scoring "roc_auc" for Support Vector Classfier

Original Owners:

National Institute of Diabetes and Digestive and Kidney Diseases

# How to run the docker image

Build docker image
```bash
docker build -t pimaMLsklearn .
```

Run the Docker image
```bash
docker run -it -p 9999:9999 pimaMLsklearn:latest
```
