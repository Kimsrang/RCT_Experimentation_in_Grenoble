# Selecting Comparable Experiment Groups for Indirect Electricity Flexibility in Grenoble Based on Similarity Measures in Electrical Consumption and Socio-Economic Context

**Author:** Kimsrang IET

## Experiment Objective

The experiment aims to investigate the potential indirect electricity flexibility through information campaigns delivered to treatment groups that encourage households to shift their 
part of electricity use toward periods to higher solar availability during the day.

The methodology is implemented into 2 notebooks:

- 1st notebook:

`Similarity Measure at Feeder Level.ipynb`

- 2st notebook:

`Distribution Plot for Socio-economic Features.ipynb`

The 1st notebook includes:

- Determine similarity measures between feeder pairs using Euclidean distance.
- Compute physical distances between feeder pairs.
- Visualization of building locations associated with feeders using interactive maps.
- Evaluation of performance indicators to assess whether experiment groups are statistically comparable in terms of electrical consumption.
- Parallel coordinate plot to easily select the balanced experiment groups

The 2st notebook includes:

- Calculate the building ratio associate with the feeder pair.
- Calculate the energy share associate with the feeder pair.
- Check the distribution plot for socio-economic features

## Execution Instructions

### Step 1: Download Input Data

Download the required data for both electrical consumption and socio-economic context in these folders 

- meshes_timeseries_clean/
- input_data/

### Step 2: Run the code in 1st notebook

`Similarity Measure at Feeder Level.ipynb`

### Step 3: Execute the 1st Notebook

The notebook performs the following tasks:

1. Load electrical consumption and socio-economic datasets.
3. Compute Euclidean-distance-based similarity measures between feeder pairs.
4. Calculate physical distances between candidate feeders.
5. Interactive map plot to visualize building locations associate with the feeders.
6. Evaluate load-profile-based performance indicators.

## Outputs of 1st notedbook

The output from the code includes:

- Feeder-pairs ranking based on the similarity scores
- Physical distance between the feeder pair
- Interactive map
- Observe the consumption behavior 
- Statistical performance indicators

## Objective

The final objective is to identify a higher comparable feeder pair in term of:

- Electrical consumption pattern
- Socio-economic context

to ensure the selected feeder pair is unbiased and balanced across all the baseline characteristics before the behavioral signals will be delivered via FaceBook one-day in advance of the intervention,
And households can be encouraged to shift their portion of electricity use from the evening peak period to the high solar availability period during the day.
