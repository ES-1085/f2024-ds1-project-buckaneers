Project proposal
================
Buckaneers

``` r
library(tidyverse)
library(broom)
```

## 1\. Introduction
We are analyzing the influence of inherent soil factors and agricultural management on soil organic matter. Our data comes from a coalition of 218 farms and fields across Wisconsin and southern Minnesota. The data was collected using single variable and regression tree analysis to examine the soil characteristics: texture, drainage, and pH in relation to tillage, animal husbandry, cover cropping, manure application, and crop rotation. 

## 2\. Data

## 3\. Data analysis plan
What variables will you visualize to explore your research questions?

We will be looking at what type of agriculture is upon the land in which the soil was tested (e.g. turkey, beef, dairy, rye, wheat, oat, corn, soy, etc.). Additionally, we will examine what soil factors are included in the analyses like description of the soil (from sandy to “muck”, drainage of soil (“very poorly drained”, “poorly drained”, “somewhat poorly drained”, “moderately well drained”, “well drained”, “somewhat excessively well drained”, and “excessively drained”, soil type (rated on a scale), pH, regions in which the soil exists (1, 2, 3, 4, 5, 6) across Wisconsin and Minnesota, and the year in which the samples were collected (2015-2017). Secondly, we will be including the variable of manure: what species did the manure come from, what form was it (liquid, solid), how many applications was the soil exposed to. Another variable included in the dataset will be the form/type of tillage of the soil: “no tillage” (vertical tillage or strip tillage, “conventional tillage” (chisel, disk or moldboard), and the number of “tillage passes” that occurred between harvest of the previous year’s crop and the planting of the current year’s crop (0 to 4). Tillage was only considered no-tillage or minimum tillage if practiced for more than 4 years.