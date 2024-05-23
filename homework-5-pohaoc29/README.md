# Hw5 - Accute Inflamations data & Communities and Crime data

### Introduction
Accute Inflamations data
- Decision Trees as interpretable models

Communities and Crime data
- Using linear model, ridge regression model, LASSO model, and PCR model
- Using L1-penalized gradient boosting tree (XGBoost)


### Data description
#### 1. Accute Inflamations data (https://archive.ics.uci.edu/dataset/184/acute+inflammations)

The data was created by a medical expert as a data set to test the expert system, which will perform the presumptive diagnosis of two diseases of urinary system.  The basis for 
rules detection was Rough Sets Theory.  Each instance represents an potential patient.

The data is in an ASCII file. Attributes are separated by TAB.
Each line of the data file starts with a digit which tells the temperature of patient.

  -- Attribute lines:
       For example, '35,9	no	no	yes	yes	yes	yes	no'
       Where:
	 '35,9'	Temperature of patient 	
	 'no'	Occurrence of nausea 	
	 'no'	Lumbar pain  	
	 'yes'	Urine pushing (continuous need for urination)  	
	 'yes'	Micturition pains  
	 'yes'	Burning of urethra, itch, swelling of urethra outlet 	
	 'yes'	decision: Inflammation of urinary bladder 
	 'no'	decision: Nephritis of renal pelvis origin
     
#### 2. Communities and Crime data (https://archive.ics.uci.edu/dataset/183/communities+and+crime)

Communities within the United States. The data combines socio-economic data from the 1990 US Census, law enforcement data from the 1990 US LEMAS survey, and crime data from the 1995 FBI UCR.
