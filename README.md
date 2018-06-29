## Why shall we care about emergent constraints in climate sensitivity? 

__The future of our climate system depends on asking the right questions. One of these questions could be: What are the most relevant emergent constraints for ECS?__

### Climate sensitivity
A measure of the response of the global climate system to a certain forcing e.g. a measure of the change (increase) in global mean temperature when there is a doubling of the atmospheric CO2 concentration. IPCC: the value is around 3 degrees Celsius, depending on positive and negative feedback effects (sea ice, water vapour, clouds, greenhouse gases); without feedback effect the change would be around 1 degree Celsius. In the long run the increase could be greater than 3 degrees since the CO2 concentration can be more than double, while in the short run the warming could be less due to the thermal inertia of the ocean (see details [here](http://news.mit.edu/2010/explained-climate-sensitivity)). 

### Emergent constraints
Reducing uncertainties in climate change projections $\longleftrightarrow$ reducing the most influential uncertainties in different climate models. [Approach](http://climate-dynamics.org/reducing-uncertainties-in-climate-projections-with-emergent-constraints-part-1-concept/): identify a relationship = _emergent constraint_ between an observable variable $$A$$ (_predictor_) and the inter-model responses B to a radiative perturbation. Observed values of A are used to __constrain__ the responses B. Weighted average of the models: difference between a model ouput for A and the observed value $\rightarrow$ outliers. Reliability: check the physical mechanisms underlying the above relationship (Hasselman model in our case), observation errors and spread etc. 
 
## Aim
__Find relevant emergent constraints and investigate their reliability.__

Particular case: global mean temperature variability. Reference: P. M. Cox, C. Huntingford, M. S. Williamson, _Emergent constraint on equilibrium climate sensitivity from global temperature variability_, Nature, 2018. 

Exploration: sea-land temperature variability. 

## Plan 
This is going to be exciting!

Step 1: Formulate the problem. Check available data. (see above)

Step 2: Find related literature. Discuss the methods involved and their adaptability to a different scenario. 

Step 3: Use the data to reproduce already validated experiments. 

Step 4: Elaborate a strategy for further explorations. 

## Methodology
CMIP5 ([Coupled Model Intercomparison Project 5](https://esgf-node.llnl.gov/projects/cmip5/)):  experimental protocol for studying coupled atmosphere-ocean general circulation models which allows for a systematic analysis in terms of model diagnosis, comparison, model validation.

HadCRUT4 ([Met Office Hadley Centre Observations](https://www.metoffice.gov.uk/hadobs/hadcrut4/index.html)) data set: 
Recent  developments  in  observational  near-surface  air  temperature  and  sea-surface  temperature analyses  are  combined  to  produce  HadCRUT4,  a  new data  set  of  global  and  regional  temperature evolution  from  1850  to  the  present.
Time series are monthly, annual and decadally smoothed series for each ensemble member of the HadCRUT4 ensemble (100).

We explore how CMIP5 models' ECS spread can be 'constrained' by different observable metrics. 


## Brief literature review 
P. M. Cox, C. Huntingford, M. S. Williamson, _Emergent constraint on equilibrium climate sensitivity from global temperature variability_, [Nature](https://www.nature.com/articles/nature25450), 2018: 
* propsed observable:  variability of global mean temperature 
* consider _Hasselman model_ for the variation in global mean temperature in response to a radiative forcing 
* 16CMIP5 models, output compared to data from HadCRUT4, anomalies relative to the time-interval 1961-1990
* de-trended data 
* emergent constraint: linear regression across 16 CMIP5 models between ECS and the metric for (de-trended) global temperature variability.  


## Our results
We successfully 
 * manipulated the available data from CMIP5 (15 models considered) and HadCRUT4 (download, de-trend, concatenate, analyze); 
 * replicated the results of Cox et. al. - see the code and the plots; 
 * explored the realiability of considering sea-land temperature as an emergent constraint. 


## Conclusions
 * the _emergent constraints method_ is relevant when exploring the behaviour of the climate system 
 
## Authors
* Goodwin Gibbins
* Lea Oljaca
* Oana Lang 







