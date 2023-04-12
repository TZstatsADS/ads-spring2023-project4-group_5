# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2023

+ Team #5
+ Project title: Machine Learning Fairness
+ Team members
	+ Luke Arceneaux	lpa2114@columbia.edu
	+ Jiahao Wei	jw4312@columbia.edu
	+ Xiaoxue Ren	xr2159@columbia.edu
	+ Mingze Xu	mx2269@columbia.edu
	+ Yiming Zhu	yz4336@columbia.edu
	+ Xia, Weijie   wx2281@columbia.edu
+ Project summary: The project observes fairness in classification, particularly on the issue of bias for Caucasions vs. African Americans in predicting the likelihood of recidivism in criminal defendants (data found in the COMPAS dataset). Our goal is to evaluate methods for improving fairness of models using different metrics of fairness. We observe 4 methods originating from 2 papers. The dataset is preprocessed and split into training, validation, and testing sets, and a logistic regression model is trained to predict recidivism. We individually apply the methods through this process and evaluate them. This is done by finding the calibration difference between the predicted outcomes for Caucasians and African Americans to assess fairness in addition to their p-rule's. The code and dataset are available on GitHub, and the project is part of ongoing research in fair classification.
	

**Contribution statement**: 
All six of us contributed equally in the project. We worked together on feature selection, data cleaning, and data wrangling. After finalize the cleaned data, we split the group into 2 mini-groups. Weijie Xia, Mingzi Xu, Xiaoxue Ren mainly worked on A2 paper and its algorithm, while Jiahao Wei, Luke Arceneaux, Yiming Zhu worked on A6. After building the models, we always meet on ZOOM to discuss the algorithm and code. All team members approve our work presented in this GitHub repository including this contributions statement. 


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
