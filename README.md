# Wine-Quality
 Develop a Wine Quality Analytics System to assess and predict the quality of wines based on their chemical composition and attributes.

 
Citation Request:
  This dataset is public available for research. The details are described in [Cortez et al., 2009]. 
  Please include this citation if you plan to use this database:

  P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
  Modeling wine preferences by data mining from physicochemical properties.
  In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

  Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016
                [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf
                [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib

1. Title: Wine Quality 

2. Sources
   Created by: Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) @ 2009
   
3. Past Usage:

  P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
  Modeling wine preferences by data mining from physicochemical properties.
  In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

  In the above reference, two datasets were created, using red and white wine samples.
  The inputs include objective tests (e.g. PH values) and the output is based on sensory data
  (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality 
  between 0 (very bad) and 10 (very excellent). Several data mining methods were applied to model
  these datasets under a regression approach. The support vector machine model achieved the
  best results. Several metrics were computed: MAD, confusion matrix for a fixed error tolerance (T),
  etc. Also, we plot the relative importances of the input variables (as measured by a sensitivity
  analysis procedure).
 
4. Relevant Information:

   The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine.
   For more details, consult: http://www.vinhoverde.pt/en/ or the reference [Cortez et al., 2009].
   Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables 
   are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

   These datasets can be viewed as classification or regression tasks.
   The classes are ordered and not balanced (e.g. there are munch more normal wines than
   excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent
   or poor wines. Also, we are not sure if all input variables are relevant. So
   it could be interesting to test feature selection methods. 

5. Number of Instances: red wine - 1599; white wine - 4898. 

6. Number of Attributes: 11 + output attribute
  
   Note: several of the attributes may be correlated, thus it makes sense to apply some sort of
   feature selection.

7. Attribute information:

   For more information, read [Cortez et al., 2009].

   Input variables (based on physicochemical tests):
   1 - fixed acidity
   2 - volatile acidity
   3 - citric acid
   4 - residual sugar
   5 - chlorides
   6 - free sulfur dioxide
   7 - total sulfur dioxide
   8 - density
   9 - pH
   10 - sulphates
   11 - alcohol
   Output variable (based on sensory data): 
   12 - quality (score between 0 and 10)

8. Missing Attribute Values: None


### Dataset Features Description

1. Fixed Acidity

Determines the tartness and crispness of the wine. Higher acidity often means a more refreshing, crisp taste.
White Wines: Generally preferred to be slightly higher for freshness and preservation.
Red Wines: Balanced acidity is crucial for good structure and aging potential.

2. Volatile Acidity

Contributes to the wine’s aroma but in excess can lead to a vinegary smell, indicating spoilage.
White Wines: Lower levels are preferred to avoid spoilage and maintain freshness.
Red Wines: Can tolerate slightly higher levels, but excessive amounts are still undesirable.

3. Citric Acid

Adds a citrusy flavor and helps in preserving the wine. Can enhance freshness and balance.
White Wines: Commonly used to boost freshness; higher levels are often more acceptable.
Red Wines: Less common and used in smaller amounts, as red wines rely more on other acids for structure.

4. Residual Sugar

Determines the sweetness of the wine. Higher residual sugar results in sweeter wines.
White Wines: Can vary widely (dry to sweet). Sweetness must match the style of the wine (e.g., dessert wines have high residual sugar).
Red Wines: Usually drier, but sweeter styles exist (e.g., Port). Excessive sweetness can mask other flavors.

5. Chlorides

Impacts the wine's taste and mouthfeel. High chloride levels can lead to a salty or off taste.
Both: Should be kept within normal ranges to avoid undesirable flavors and ensure quality.

6. Total Sulfur Dioxide

Acts as a preservative to prevent oxidation and spoilage. Can also impact the wine’s aroma and taste.
White Wines: Generally limited to around 150 mg/L in EU. Essential for freshness and preventing spoilage.
Red Wines: Can tolerate slightly higher levels (up to 250 mg/L) due to their composition and aging process.

7. Density

Reflects the wine’s alcohol content and sugar levels. Denser wines often have higher alcohol or sugar.
Both: Density helps in assessing wine style and balance. Typical ranges are used to ensure consistency and quality.

8. pH

Influences the wine's stability, taste, and aging potential. Lower pH means higher acidity and more freshness.
White Wines: Preferred pH is between 2.9 and 3.6 for crispness and preservation.
Red Wines: Typically between 3.2 and 3.8, affecting structure and aging potential.

9. Sulphates

Adds to the wine’s flavor profile and preservation. Can impact mouthfeel and stability.
Both: Should be balanced to enhance flavor without overpowering the wine.

10. Alcohol

Impacts the body, sweetness, and overall balance of the wine. Higher alcohol can lead to a fuller body and potentially sweeter taste.
Both: Should align with the wine style. Excessive alcohol can overshadow other flavors, while too little can result in a thin wine.