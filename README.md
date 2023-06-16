# DAS-Group-13

## Dataset
Datasets 10-15 come from the Coffee Quality Database (CQD). The database contains information from the Coffee Quality Institute which is a non-profit organisation working internationally to improve the quality of coffee and the lives of the people who produce it. Each of the 5 datasets contain information on features of coffee and its production, including an overall score of quality. You will have access to the following variables, recorded by batch. 
## Variables
• country_of_origin – Country where the coffee bean originates from. 
• aroma – Aroma grade (ranging from 0-10)
• flavor – Flavour grade (ranging from 0-10)
• acidity – Acidity grade (ranging from 0-10)
• category_two_defects – Count of category 2 type defects in the batch of coffee beans tested.
• altitiude_mean_meters – Mean altitude of the growers farm (in metres)
• harvested – Year the batch was harvested
• Qualityclass – Quality score for the batch (Good - ≥ 82.5, Poor - <82.5). Note: 82.5 was selected as 
the cut off as this is the median score for all the batches tested. 
## Task
Imagine you have been asked by a local coffee farmer to investigate the following question of interest:
• What influence do different features of coffee have on whether the quality of a batch of coffee is classified 
as good or poor?

## Conclusion
- GLM stepwise with interaction terms: (aroma:flavor, flavor:acidity, aroma:acidity) is the best fitted model with lowest AIC and BIC
- Aroma, Flavor and acidity are the main contributors to the quality of coffee
- Interaction of Aroma and flavor will do negative effect in coffee quality
- Columbia, Thailand have better coffee farming conditions
- Uganda, India, Mexico have worse coffee farming conditions



