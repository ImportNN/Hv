# Hv
## If you plan on using the PKL(model) you just need to do two things:
* Import the pkl file with joblib
* You can feed the model all the inputs the dataframe has as the pkl already handles the info it needs but if you deserve to do it the lean way the mandatory columns you need are :
  * CurrentPrice
  * CoListAgentMLSID
  * ListPrice
  * LotSizeArea
  * LotSizeAreaSQFT
  * OriginalListPrice
  * RATIO_CurrentPrice_By_SQFT
  * SqFtTotal
  * UnexemptTaxes
  * ElementarySchoolName
## If you want to follow a basic EDA I've done to understand the basics of the dataframe and important features please check the "First exploration" notebook
## If you want to follow how I've created the model please check the "Model" notebook
