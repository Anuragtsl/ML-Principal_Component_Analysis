# ML-Principal_Component_Analysis

I have applied Principal Component Analysis on Heart Disease Dataset.

In this I've used Python’s Famous libraries like [Numpy](), [Pandas](), [Matplotlib](), [Seaborn](), and [Sklearn]() for Analysis and Dimension Reduction of Data.

I've used [Jupyter Notebook]() for coding!

**Download the dataset from [here]()!**

# About Dataset

The dataset contains the following features:

* age(in years)
* sex: (1 = male; 0 = female)
* cp: chest pain type
* trestbps: resting blood pressure (in mm Hg on admission to the hospital)
* chol: serum cholestoral in mg/dl
* fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* restecg: resting electrocardiographic results
* thalach: maximum heart rate achieved
* exang: exercise induced angina (1 = yes; 0 = no)
* oldpeak: ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
* ca: number of major vessels (0-3) colored by flourosopy
* thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
* target: 1 or 0

# Inference

First 2 Principal components:

1st PC: 74.76% 2nd PC: 15.04%

Total: 89.8%

* **First dimension:** From the above plot it is noticed that the weight is large and positive for chol, while being slightly positive for sex and cp which means that customers who score highly in this component will have very little dimpact on heart disease whereas people having higher cholestrol have greater chances of heart disease.

* **Second Dimension:** From the above plot it is noticed that the weight is large and negative for thalach and slightly negative for cp,chol and slope, which means that patients who score high in this component will have very less chances of heart disease. Whereas age and trestbps are moderatively positive.

***Follow [notebook]() for more!!***

# Preview

![Image1]()

![Image2]()

![Image3]()


#Njoy!
