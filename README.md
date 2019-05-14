# Immunohistochemical assessment of basal and luminal markers in non-muscle invasive urothelial carcinoma of bladder

Maria del Carmen Rodríguez Peña (1), Alcides Chaux (2), Marie-Lisa Eich (1), Aline C. Tregnago (3), Diana Taheri (4), Walaa Borhan (5), Rajni Sharma (3), M. Katayoon Rezaei (6), and George J. Netto (1,3)

1. Department of Pathology, University of Alabama at Birmingham, Birmingham, AL, 35233, USA
2. Department of Scientific Research, School of Postgraduate Studies, Norte University, Asunción, Paraguay
3. Department of Pathology, Johns Hopkins University, Baltimore, MD 21287, USA
4. Department of Pathology, Isfahan Kidney Diseases Research Center, Isfahan University of Medical Sciences, Isfahan, Iran
5. Department of Pathology, College of medicine, Taibah University, Madinah, Saudi Arabia
6. Department of Pathology, George Washington University, Washington, DC 20037

**Corresponding author:** George J. Netto MD, Department of Pathology, The University of Alabama at Birmingham, WP Building, Suite P230, 619 19th Street South Birmingham, AL 35249-7331.    
<gnetto@uabmc.edu>    
ORCID: 0000000339159134

**Keywords:** molecular classification, basal, luminal, immunohistochemistry, urothelial carcinoma, non-muscle invasive bladder cancer

## Material and methods
### Patient selection and TMA building
The dataset was composed of 411 tissue microarray (TMA) spots of non-muscle invasive bladder urothelial carcinoma (NMIBUC) and paired normal urothelium built from 60 pathologic cases, which corresponded to 193 patients with NMIBUC. We built the TMAs using a previously described method.

### Immunohistochemistry
We evaluated the immunohistochemical expression of basal (CK5/6 and CD44) and luminal markers (CK20, GATA3, ER, HER2, and Uroplakin). For each marker, the percentage of positive tumor cells was recorded at each TMA spot.

### Data analysis
Markers levels were sumarized using the average (arithmetic mean) percentage of positive tumor cells for each pathologic case. Data analysis was carried out using paired events. For any case, the paired event consisted in the pair formed by 2 consecutive diagnoses during follow-up. Thus, a case could have one or more paired events. For each marker, the considered outcomes included:

1) **Tumor recurrence at next biopsy:** tumor reappeared showing a similar or lower-grade/stage lesion.

2) **Tumor recurrence at any biopsy:** tumor had recurred at least once during follow-up.

3) **Tumor grade progression at next biopsy:** tumor reappeared showing a higher-grade lesion.

4) **Tumor grade progression at any biopsy:** tumor had showed grade progression at least once during follow-up.

5) **Tumor stage progression at next biopsy:** tumor reappeared showing a higher-stage lesion.

6) **Tumor stage progression at any biopsy:** tumor had showed stage progression at least once during follow-up. 

Expression levels were compared for each outcome using the Mann-Whitney's U test or the Kruskal-Wallis rank sum test. Odds ratios (and corresponding 95% confidence intervals) for each outcome were estimated using conditional binary logistic regression. In addition, patterns of markers expressions were evaluated using principal component analysis (PCA).

Finally, each case was categorized as having either higher basal or luminal expression based on 2 approaches. 1) For the first approach, a case was categorized as having higher basal expression if CK5/6 or CD44 showed the highest median value among all markers, and having as higher luminal expression if CK20 or Uroplakin showed the highest median value among all markers. 2) For the second approach, each case was categorized as having either higher basal or luminal expression based on which group of markers had the highest sum of median values. A case was categorized as higher basal expression if the sum of the median values of CK5/6 and CD44 was higher than the sum of median values of CK20 and Uroplakin. The case was categorized as higher luminal expression otherwise. These categories were compared against outcome using Pearson's chi-squared test.

To prevent family-wise error rates due to multiple comparisons, P values were adjusted using Bonferroni's method. For hypotehsis testing, statistical significance was established at P < 0.05 for 2 tails of distribution. Data was analyzed and plots were generated using R 3.5.3 (2019-03-11) from the R Foundation for Statistical Computing (Vienna, Austria).

## Results
1. [Cohort features](Report/01-BL-NMIBUC-Cohort.ipynb)
2. [Outcome features](Report/02-BL-NMIBUC-Outcome.ipynb)
3. [Regression models](Report/03-BL-NMIBUC-Regression.ipynb)
4. [Survival analysis](Report/04-BL-NMIBUC-Survival.ipynb)
5. [Sequential expression analysis](Report/05-BL-NMIBUC-Sequential.ipynb)
6. [Expression patterns](Report/06-BL-NMIBUC-Patterns.ipynb)
