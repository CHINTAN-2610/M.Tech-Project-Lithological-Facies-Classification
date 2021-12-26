# M.Tech-Thesis-Facies-Identification

## Problem Statement : 
                       
                       Subsuraface contains various liothological facies. Through which many are courser and many are finers. 
                       Many facies responsible for HC accumulation/generation  and many responsible for migration.
                       It is importenet to identify facies present inside subsurface as petroleum engineer to get idea about HC acculumation.
                       Moreover, as geologist it is importent to recognize geological activities below subsurface.
                       
 ## Workflow : 
 
 ### Features include 
               
               five wireline log curves include :
               gamma-ray (GR), 
               resistivity logging (ILD_log10), 
               photoelectric effect (PE), 
               neutron-density porosity difference and 
               average neutron-density porosity (Delta PHI and PHIND) 
               
               Two geologic constraining variables: nonmarine-marine indicator (NM_M) and relative position (RELPOS) 
               
  ### Label include 
   
               The discrete facies (classes of nine rocks) are:
               Nonmarine sandstone
               Nonmarine coarse siltstone
               Nonmarine fine siltstone
               Marine siltstone and shale
               Mudstone (limestone)
               Wackestone (limestone)
               Dolomite
               Packstone-grainstone (limestone)
               Phylloid-algal bafflestone (limestone)
               
  ### Methodology 
     
![workflow](https://user-images.githubusercontent.com/83824396/147400817-603d2359-9da7-480e-8e33-a31d8b8d3746.jpg)

### EDA 
           EDA performed to replace missing by generating synthesis PE log data using random forest regression.


### Algorithm Applied 

             1. Logistic Regression
             2. KNN
             3. SVM
             4. RANDOM FOREST
             
### Result 

              A. Confusion matrix using excate facies as true classification
              
 <img width="584" alt="Result 1" src="https://user-images.githubusercontent.com/83824396/147401328-9a709b47-747e-4313-ae47-b17f16516007.png">


              B. Confusion matrix using adjusted facies as true classification
  
  <img width="584" alt="result2" src="https://user-images.githubusercontent.com/83824396/147401355-37174493-4d5d-48ea-8043-bd4a61b0a566.png">






                       
    
