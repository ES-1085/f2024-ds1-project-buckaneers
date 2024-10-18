# data

Place data file(s) in this folder.

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

## name of data file



## variable of names 

- `FieldID`: Internally labeling system to identify fields.
- `Region`: Six regions identified.
- `Sampling Time`: Samples were collected one of two general time periods.
- `Year`: Samples collected over three years.
- `Sand`: percent, obtained as average of NRCS soil survey texture class.
- `clay`: percent, obtained as average of NRCS soil survey texture class.
- `Drainage`: obtained from NRCS soil survey.
- `SoilType`:obtained from NRCS soil survey.
- `pH`:unitless, Directly measured.
- `tile`: obtained from farmer information.
- `OM`:Directly measured as loss on ignition.
- `TOC`:Directly measured with elemental analyzer.
- `Date_Of_TOC & TN`: Date of measurement (some samples were reanalyzed.)
- `TN` : Directly measured with elemental analyzer.
- `Rtn` : Description of actual crop rotation, obtained from farmer information.
- `rtnNumber` : General category of crop rotation, determined from Rtn.
- `PreviousCrop` : Category of previous crop, obtained from farmer information.
- `Ncredit_lb/ac` : N credit from previous crop being alfalfa (90 lb-N/ac); used in total N application calculation.
- `Ncredit_kg/ha' : Ncredit_lb/ac converted to kg/ha.
- 'CvrPriorYr' : f cover crops were applied the previous year or not, obtained from farmer information.
- `cvrsSpeciesLgTm` : cover crop species planted if there was a cover crop in prior year, obtained from farmer information.
- `cvrs5yrs` : Number of times a cover crop was planted in the past five years, obtained from farmer information.
-`SpringfallTillPasses` : Occurrence of last tillage during the past 12 months, obtained from farmer information.
- `tillType` : Category of tillage practice, obtained from farmer information
- `mnr5yrs` : Number of times manure was applied during the past five years, obtained from farmer information.
- `mnrSource` : Species of animal from which manure was derived.
- `mnrSolid` : State of manure 
- `mnrN_lb/ac` : The plant available nitrogen applied from manure (as determined from conversions provided in Laboski & Peters, 2012), obtained from either manure analysis provided from the farmer (which is a direct measure of the total N content of the manure) or from estimates provided by Laboski & Peters, 2012 (which are based on manure type and application method.)
- `mnrN_kg/ha` : mnrN_lb/ac converted to kg/ha (data originally obtained a english units.)
- `mnrTiming` : Timing of most recent manure application if applied in the past 12 months, obtained from farmer information
- `fertN_lb/ac` : Total fertilizer nitrogen applied, obtained from from farmer information.
- `fertN_kg/ha` : fertN_lb/ac converted to kg/ha (data originally obtained as english units.)
- `totalN_lb/ac` : sum of 'Ncredit_lb/ac', 'mnrN_lb/ac', and 'fertN_lb/ac'.
- `totalN_kg/ha : sum of 'Ncredit_kg/ha', 'mnrN_kg/ha', and 'fertN_kg/ha'.

-Categorical variables and the assigned value description
- `Region 1` : Northeast WI
- `Region 2` : Dry Run (HUC 0703000510)
- `Region 3` : Elk Creek (HUC 0704000503)
- `Region 4` : Jersey Valley (HUC 0707000602)
- `Region 5` : Southeast WI
- `Region 6` : Southern Minnesota

- `Sampling Time 1` : mid-April
- `Sampling Time 2` : Late-June

- `Year 1` : 2015
- `Year 2` : 2016
- `Year 3` : 2017

- `Drainage 1` : Very poorly drained
- `Drainage 2` : Poorly drained
- `Drainage 3` : Somewhat poorly drained
- `Drainage 4` : Moderately well drained
- `Drainage 5` : Well drained
- `Drainage 6` : Somewhat excessively well drained
- `Drainage 7` : Excessively drained

- `SoilType 1` : Sand
- `SoilType 2` : Loamy Sand
- `SoilType 3` : Fine Loamy Sand
- `SoilType 4` : Sandy Loam
- `SoilType 5` : Silt Loam
- `SoilType 6` : Loam
- `SoilType 7` : Silty Clay Loam
- `SoilType 8` : Clay Loam
- `SoilType 9` : Muck

- `tile 1` : Yes, field has tile drains
- `tile 2` : No, field does not have tile drains
- `tile 3` : No data

- `Crop Rotation 1` : Continuous corn
- `Crop Rotation 2` : Corn-soybean
- `Crop Rotation 3` : Small grain in rotation
- `Crop Rotation 4` : Perennial legume in rotation
- `Crop Rotation 5` : No data

- `Previous crop 1` : Corn silage
- `Previous crop 2` : Corn grain
- `Previous crop 3` : Soybean
- `Previous crop 4` : Alfalfa
- `Previous crop 5` : Other (small grain or vegetable)
- `Previous crop 6` : No data

- `CvrPriorYr 1` : Yes, a cover crop was planted
- `CvrPriorYr 2` : No, a cover crop was not planted

- `cvrs5yrs 1` : 1
- `cvrs5yrs 2` : 2
- `cvrs5yrs 3` : 3
- `cvrs5yrs 4` : 4
- `cvrs5yrs 5` : 5
- `cvrs5yrs 6` : No Data

- `SpringfallTillPasses 1` : No tillage
- `SpringfallTillPasses 2` : 1
- `SpringfallTillPasses 3` : 2
- `SpringfallTillPasses 4` : 3
- `SpringfallTillPasses 5` : 4
- `SpringfallTillPasses 6` : No data

- `tillType 1` : No tillage (fields that have been managed without tillage for at least five years)
- `tillType 2` : Minimum tillage (strip tillage and vertical tillage)
- `tillType 3` : Conventional tillage (moldboard, chisel, or disc tillage)
- `tillType 4` : No data

- `mnr5yrs 1` : 0
- `mnr5yrs 2` : 1
- `mnr5yrs 3` : 2
- `mnr5yrs 4` : 3
- `mnr5yrs 5` : 4
- `mnr5yrs 6` : 5
- `mnr5yrs 7` : No data

- `mnrSolid L` : liquid
- `mnrSolid S` : solid
- `mnrSolid B` : both liquid and solid
- `mnrSolid none` : no manure

- `mnrTiming 0` : None
- `mnrTiming 1` : Summer prior
- `mnrTiming 2` : Fall prior
- `mnrTiming 3` : Winter prior

 

>>>>>>> 1a58042174c16e488acc123708430476040a4fba
- ...
