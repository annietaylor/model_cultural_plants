# model_cultural_plants
These are the Python notebooks that I used to process all of the input datasets for and output results from the Software for Assisted Habitat Modeling (SAHM) species distribution modeling package. The research related to this analysis is submitted for publication and will be available as soon as possible. I ran all of these notebooks in ArcGIS Pro 3.0 for easy access to the arcpy package and spatial datasets.  

I ran SAHM 2.0 with version 2.2.2 of the open source workflow platform VisTrails. You can read more about [VisTrails](https://www.vistrails.org//index.php/Main_Page) and [SAHM](https://doi.org/10.1111/j.1600-0587.2012.07815.x). 

### Notebooks
1. iNat_SAHM.ipynb: Create species observation datasets from research grade iNaturalist observations and combine any existing observations from my own datasets. Also used to create target group background points using all recent research grade observations of plants. 
2. Combine_Result_Rasters.ipynb: Uses the output file structure of SAHM to project, clip, and combine all of the resulting binary presence-absence rasters for a given species. 
3. Extract_Model_Outputs_2022.ipynb: Uses the output file structure of SAHM to calculate the mean AUC and PCC values of the ten cross validation runs for each of the five models. Also extracts variable importance values. 
4. MESS_Model_Outputs_2022.ipynb: Reclassify and combine multivariate environmental similarity surfaces (MESS) maps for each model run to reveal areas of model extrapolation. Also uses the default output file structure of SAHM. 


Update 1.4.2023: Added more comments for clarify, reduced notebook outputs, and fixed issues with the iNaturalist API.

Update 7.11.2022: More detailed instructions and code annotations will be added in the coming weeks. 
