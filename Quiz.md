# Edit this file  

## Using Thunor at thunor.app.vanderbilt.edu, answer the following questions:

You can access the plots for afatinib treatment using DIP rate or viability at 72 h by following [this link](https://thunor.app.vanderbilt.edu/plots?dataset=13&colsLg=3&colsMd=2&plotdata=plotType%3Ddrc%26datasetId%3D13%26dataset2Id%3D%26useCellLineTags%3Doff%26c%3D8%26c%3D9%26c%3D10%26c%3D11%26c%3D12%26c%3D17%26c%3D18%26useDrugTags%3Doff%26d%3D5%26colorBy%3Doff%26drMetric%3Ddip%26drcType%3Drel&plotdata=plotType%3Ddrc%26datasetId%3D13%26dataset2Id%3D%26useCellLineTags%3Doff%26c%3D8%26c%3D9%26c%3D10%26c%3D11%26c%3D12%26c%3D17%26c%3D18%26useDrugTags%3Doff%26d%3D5%26colorBy%3Doff%26drMetric%3Dviability%26drcType%3Drel)  

Alphabetical list of cell lines for reference (reorder as instructed below): BR1, DS3, DS7, DS8, DS9, MGH, PC9

### Dose response parameters for afatinib  
1) What is the rank ordering of the cell lines by activity area (observed) (from lowest to highest) using DIP rate as the effect metric?  

answer: 

2) What is the rank ordering of the cell lines by activity area (observed) (from lowest to highest) using 72 h viability as the effect metric?

answer: 

### Explore the afatinib-induced responses as time courses and dose-response curves  
3) Compare the afatinib-induced time courses and dose-response curves of the PC9 variants using Thunor. Which of the following is FALSE?  
    a) The "Activity Area observed" value of MGH is the highest compared to all other cell lines when the 72 h viability is used as the response metric.  
    b) DS3 has the highest "Activity Area observed" value compared to all other cell lines when DIP rate is used as the response metric.  
    c) The DIP rate values of MGH at all concentrations of afatinib < 1µM are positive values.  
    d) The cell counts of MGH drop significantly after 72 h but increase slightly thereafter, which results in a positive DIP rate that may not reflect the overall decrease in cell number induced by afatinib.  
    e) The measured DIP rate values of DS3 at all concentrations of afatinib > 300 pM are negative, indicating net cell death.  

answer: 

### Explore other data in the dataset

4) Choose the value closest to the DIP rate-based $Emax_{(observed, relative)}$ of DS3 treated with trametinib reported by Thunor:  
    a) -0.109  
    b) -0.180  
    c) 0.215  
    d) 0  
    
answer: 

5) What is the EC50 calculated for paclitaxel on BR1 using DIP rate as the effect metric?  
    a) 0.146 nM  
    b) 3.9688 µM  
    c) Not reported (the model could not be fit to the data)  
    d) 0  
    
answer:   

6) From the assignment Python notebook, what is the $EC_{50}$ value of paclitaxel on BR1 from the fit `ll4` function to DIP rates BEFORE removing the artifactual data?  

answer:   
  
7) From the assignment Python notebook, what is the $EC_{50}$ value of paclitaxel on BR1 from the fit `ll4` function to DIP rates AFTER removing the artifactual data?  

answer:   
  
8) From the assignment Python notebook, what is the $E_{max}$ value from the fit `ll3` function to response ratio AFTER removing the artifactual data?

answer:   
  
