# Donor Site Morbidity 
### Model Starter Code
To load the model, run the following in the command line:
```
import pickle
loaded_model = pickle.load(open(filename, 'rb'))
```
where filename is the name of the saved model file


After loading model, run the following line
```
test = pd.DataFrame({'Age': [num], 'BMI': [num], 'Mean.flap.volume': [num],'length.of.surgery..minutes.':[num]})
loaded_model.predict_proba(test)
```
where "num" is an integer or a float, and the variables of interest include age, BMI, mean flap weight, and length of surgery in minutes

### Python Version
>3.7.4
