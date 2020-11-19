#creating pandas from dicit

import pandas as pd 
   
data = [{'area': 'new-hills', 'rainfall': 100, 'temperature': 20}, 
         {'area': 'cape-town',  'rainfall': 70, 'temperature': 25}, 
         {'area': 'mumbai',  'rainfall': 200,  'temperature': 39 }] 
  
df = pd.DataFrame.from_dict(data) 
  
df 


#filtering DF 
df.loc[df['column_name'] == some_value]

#iterate over rows in Pandas Dataframe
for index, row in df.iterrows(): 
    print (row["area"], row["rainfall"]) 
