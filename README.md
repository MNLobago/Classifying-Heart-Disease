# Introduction

[Coronary artery](https://en.wikipedia.org/wiki/Coronary_artery_disease) disease is a heart condition involving a reduction of blood flow into the heart caused by the narrowing of blood vessels due to the build up of [atherosclerotic plaque](https://en.wikipedia.org/wiki/Atheroma). This heart disease is the most common type and if blockage becomes severe enough can lead to heart attacks/failure.

The goal of this project is to build a model using classification with logistic regression to predict the probability of coronary heart disease in a patient.

Source for the data used in this project is from Heart Disease Dataset from the UCI Machine Learning Repository. Dataset contains the following features:


## Predictive Variables
* age: age in years

* sex: gender

     * Value 0: female
     * Value 1: male

* cp: chest pain type

     * Value 1: typical angina
     * Value 2: atypical angina
     * Value 3: non-anginal pain
     * Value 4: asymptomatic

* trestpbs: resting blood pressure (in mm Hg on admission to the hospital)

* chol: serum cholestoral in mg/dl

* fbs: (fasting blood sugar > 120 mg/dl)

      * Value 0: false
      * Value 1: true

* restecg: resting electrocardiographic results

      *  Value 0: normal
      *  Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
      *  Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

* thalach: maximum heart rate achieved

* exang: exercise induced angina

      * Value 0: no
      *  Value 1: yes

* oldpeak: ST depression induced by exercise relative to rest

* slope: the slope of the peak exercise ST segment

      * Value 1: upsloping
      * Value 2: flat
      * Value 3: downsloping

* ca: number of major vessels (0-3) colored by flourosopy

* thal:

      * Value 3: normal
      * Value 6: fixed defect
      * Value 7: reversable defect