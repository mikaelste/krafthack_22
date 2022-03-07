# krafthack_22
#Krafthackathon 2022

## The winner* team
@mikaelste, 

### Important notes:
- Regulate 120m og 538m total drain
- 3 TWH / year
- Runner = 40T 
- 0.7m long bolts (mounted strain gauge)
- Main valve: Drop in temperature = flowing water
- Start unit (full speed of water): 5min = 300s
-*Understand* what is normal

Unit 4:
- **Found crack** on lower cover:
  -> 2300Tonnes
  -> 120 bolts for 53mm dimention
 
 ## **WHAT TO DO**?
 - Simulation found that the crack came from the manufacturer (from corrotion from 820degrees)
 - Have been there for 40 years
 - Will imply changes to material (makes the steel softer)
 - Crack itself will not allow water to flow -> Softer steel -> more strain and wear on the bolts

--> Turbine supplier told us:
  - YES! End of lifetime estimate will shorten for the bolts
  - Important to know if the bolts will survive

**What have we done?**
- Mounted sensors:
--> HAve to find out what/if we have missed anything

# **The challenge** --> Predict the **tensile value of bolts** according to load
- Only have dataset from unit 4
- Only have data from one main valve (leading water to deck)
- Look away from other units
--> Operating conditions
--> bolt condition (strain gauges -> vertical and horizional distortion)
--> Vibration

**Operating conditon important!** -> Se sensor data description
input_dataset.parquet x 3 (nr2 most important)
sensor_metadata.pdf
bolt_pretension.csv

## **KEEP IN MINDS**
- Seasonal data
- Bolt proximity to crack
- Time since last run *important
- Time gaps in the data (due to connectivity issues)
--> Your output is expected on the same timeline as prediction_output

TRAIN AND BUILD MODELS FOR ALL BOLTS

### Important for the Judges 
Mean absolute percentage error -> Average across bolts
