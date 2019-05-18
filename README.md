
<strong>Project Goal:</strong><br>
The objective of this project is to develop computational algorithm that can accurately detect cardiovascular related diseases. The dataset used in this project was obtained from the publically available UCI repository heart disease dataset. This dataset has been considered the benchmark dataset in the computational cardiovascular space. The features used in the development of this model are considered medically relevant attributes(Age,sex,cp,rest bps,chol,fbs,restecg,thalach,exang,oldpeak,slope,ca,thal,class) as they significantly contribute to the progression of cardiovascular disease.<br>


<strong>Heart Disease</strong><br>
Endothelial Cells (ECs) lining the walls of blood vessels are referred to as the “governing intelligence” of vascular health <sup>1</sup>  . However, prolonged use of alcohol, cigarettes, lack of exercise, increased stress levels and genetic factors causes inflammation which damages the EC layer, thus preventing them from performing their normal functions. Continuous damage to the EC layer has been implicated in vascular diseases such as atherosclerosis (see video below). Atherosclerosis is responsible for more than 80% of all cardiovascular disease related deaths. Atherosclerosis can affect any artery in the body including but not limited to the heart, leg, kidney, brain and pelvis. This means that based on the artery that is affected athersclerosis can lead cardiovascular realated diseases such as coronary artery disease,carotid artery disease,peripheral artery disease and chronic kidney disease.

Atherosclerosis and associated cardiovascular diseases are the leading causes of death in the developed world (accounting for one in three of all deaths), and developing world <sup>2</sup>. Atherosclerosis is an inflammatory disease that affects blood vessel walls of the arterial tree <sup>3</sup>, through a cascade of events that involves lipid infiltration and accumulation in blood vessel walls. As these fatty lesions enlarge and calcify, they cause the arterial lumens to narrow or to become vulnerable to rupture and occlusion. The initiating event in atherosclerosis is injury to the blood vessel wall, resulting in endothelial dysfunction<sup>4</sup>. This disruption of the normal homeostatic regulatory functions of the endothelium initiates a sequence of events that are key features of atherosclerosis. These events include: increased permeability, reduced endothelium-mediated vasodilation, enhanced endothelial cell turnover, increased expression of adhesion molecules and other inflammatory genes of ECs, and vascular smooth muscle cells proliferation, finally leading to plaque formation, plaque rupture, thrombosis, and tissue infarction. While the exact causes of arthrosclerosis are unknown; endothelial dysfunction seems to be the initiating event, and is associated with many systemic risk factors including low HDL, hypertension, high LDL, and diabetes, among others.<br>

<strong>Gaps</strong><br>
While the use of pharmacuetical "drugable targets," such protein enzymes, receptors, or channels agents have led to a significant improvement in health outcomes of patients with atherosclerosis. Myron L. Weisfeldt et.al (2007)<sup>5</sup>,suggested that unlike treaments developed for infectious diseases they offer no immediate cure as they require longerm use. Thefore, the question remains: Can Big Data analytics or other computational intelligence techniques be utilized for early dectection of heart disease?<br>

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/ecuCECYhw_M/0.jpg)](https://www.youtube.com/watch?v=ecuCECYhw_M)<br>
[Reference: National Heart, Lung and Blood Institue](https://www.nhlbi.nih.gov/health/health-topics/topics/atherosclerosis)



<strong>The Dataset:</strong><br>
This data was obtained from Cleveland Clinic Foundation (obtained from the UCI machine learning repository). The purpose of this project is to develop a model that predicts the presence or absence of heart disease in a patient. While the databases have 76 raw attributes, only 14 of them are actually used. They include:

<strong>Detailed Attribute Information:</strong>

1. Age: Age in years
2. Sex: 1 = male; 0 = female
3. cp: Chest pain type
	- Value 1: typical angina
	- Value 2: atypical angina
	- Value 3: non-anginal pain
	- Value 4: asymptomatic
4. trestbps: Resting blood pressure (in mm Hg on admission to the hospital)
5. chol: Serum cholestoral in mg/dl
6. fbs: Fasting blood sugar > 120 mg/dl(1 = true; 0 = false)
7. restecg:Resting electrocardiographic results -- Value 0: normal
	- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05mV
	- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8. thalach: Maximum heart rate achieved
9. exang: Exercise induced angina (1 = yes; 0 = no)
10. oldpeak: ST depression induced by exercise relative to rest
11. slope: Slope of the peak exercise ST segment
	- Value 1: upsloping
	- Value 2: flat
	- Value 3: downsloping
12. ca: Number of major vessels (0-3) colored by flourosopy
13. thal: The status of the heart; 3 = normal; 6 = fixed defect; 7 = reversable defect
14. num(the predicted attribute): diagnosis of heart disease (angiographic disease status)
	- Value 0: < 50% diameter narrowing
	- Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 through 68 are vessels)

<strong>References:</strong>
1. http://www.everistgenomics.com/content/angiodefender/overview.htm
2. Malek AM, AlperSL,IzumoS. Hemodynamic shear stress and its role in atherosclerosis. JAMA;282:2035 42,1999
3. Spaet, T.H. and Editor, Progress in Hemostasis and Thrombosis, Vol.7.364 pp,1984.
4. Curtiss LK, Tobias PS. Emerging role of Toll-like receptors in atherosclerosis. J Lipid Res; 50(suppl):S340 –S345,2009.
5. Weisfeldt,M.L.,Susan J. Zieman;Health Aff January 2007 vol. 26 no.1 25-37

