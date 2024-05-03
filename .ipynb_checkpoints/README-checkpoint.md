# matplotlib_challenge
UNC class challenge 5 assignment

Pymaceuticals, Inc.

The purpose of this clinical study was to compare the effects of Pymaceuticals' Capomulin against other squamous cell carcinoma (SCC) treatments. This study included 249 mice diagnosed with SCC tumors that received a range of drug regimens over the course of 45 days. Tumor development was observed and  measured at specific timepoints throughout the trial. Other drug treatments included in this study were Ceftamin, Infubinol, Ketapril, Naftisol, Propriva, Ramicane, Stelasyn, Zoniferol, and a placebo,

The treatment drugs Capomulin and Ramicane were observed more frequently during this 45 day time period providing a larger dataset for analysis. When comparing the average tumor volume for mice receiving these treatments, the central tendency, standard deviation and standard error were nearly identical. Other drug treatments showed much higher tendencies in these same areas. Distribution of final tumor volumes also results in nearly identical results for Capomulin and Ramicane, with Capomulin having a slightly higher median and smaller IQR. Infubinol and Ceftamin’s results indicated larger tumor volumes with greater variability and possible outliers in the dataset.

The tumor volume for mouse I509, treated with Capomuli, increased for the first 21 days of the trial with a steady decrease for the remainder of the study. A positive correlation between tumor volume and weight was also observed with the Capomulin drug regimen. 

In conclusion, Capomulin outperformed all but one other drug treatment, included in this study, in decreasing the tumor volume of mice with SCC. Capomulin showed similar results of decrease with  Ramicane. 



Technologies used to analyze and visual data: 
matplotlib, pands, scipy, numpy



Credits:
- Duplicate Mouse ID error code was solved by Juson (tutor) by switching () to []
- Xpert Learning Assistant provided input for () within the .agg code
- Xpert Learning Assistant provided 'mouse_rows = mouse_rows.sort_values(ascending=False)' code to print resuts in descending order
- Xpert Learning Assistant provided 'sex_dist.reindex' to display male results on the top half of the pie chart
- Subset code 'tumor_volumes = treatment_data['Tumor Volume (mm3)']' and 'tumor_vol_data.append(tumor_volumes)' provided by peer, Zach
- Xpert Learning Assistant provided insite identify errors in code 'capomulin_data = clean_results[(clean_results['Mouse ID'] == mouse_id) & (clean_results['Drug Regimen'] == 'Capomulin')]'
    


The purpose of this clinical study was to compare the effects of Pymaceuticals' Capomulin against other squamous cell carcinoma (SCC) treatments. This study included 249 mice diagnosed with SCC tumors that received a range of drug regimens over the course of 45 days. Tumor development was observed and  measured at specific timepoints throughout the trial. Other drug treatments included in this study were Ceftamin, Infubinol, Ketapril, Naftisol, Propriva, Ramicane, Stelasyn, Zoniferol, and a placebo,

The treatment drugs Capomulin and Ramicane were observed more frequently during this 45 day time period providing a larger dataset for analysis. When comparing the average tumor volume for mice receiving these treatments, the central tendency, standard deviation and standard error were nearly identical. Other drug treatments showed much higher tendencies in these same areas. Distribution of final tumor volumes also results in nearly identical results for Capomulin and Ramicane, with Capomulin having a slightly higher median and smaller IQR. Infubinol and Ceftamin’s results indicated larger tumor volumes with greater variability and possible outliers in the dataset.

The tumor volume for mouse I509, treated with Capomuli, increased for the first 21 days of the trial with a steady decrease for the remainder of the study. A positive correlation between tumor volume and weight was also observed with the Capomulin drug regimen. 

In conclusion, Capomulin outperformed all but one other drug treatment, included in this study, in decreasing the tumor volume of mice with SCC. Capomulin showed similar results of decrease with  Ramicane. 
 
