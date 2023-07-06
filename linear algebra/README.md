# Composite Project - 2
## Data
The following data is available:<br>
Data Description:<br>
<b>Technological Process:</b>
- Rougher feed - raw material
- Rougher additions (or reagent additions) - flotation reagents: Xanthate, Sulphate, Depressant
    - Xanthate - xanthate (promoter or flotation activator)
    - Sulphate - sulfate (sodium sulfide in this production)
    - Depressant - depressant (sodium silicate)
- Rougher process - flotation
- Rougher tails - tailings
- Float banks - flotation cells
- Cleaner process - cleaning
- Rougher Au - rougher gold concentrate
- Final Au - final gold concentrate

<b>Stage Parameters:</b>
- air amount - air volume
- fluid levels - liquid level
- feed size - feed particle size
- feed rate - feed rate

<b>Feature Naming:</b></br>
The feature names should be in the following format:
`[stage].[parameter_type].[parameter_name]`
Example: `rougher.input.feed_ag`
Possible values for the `[stage]` block:
- rougher - flotation
- primary_cleaner - primary cleaning
- secondary_cleaner - secondary cleaning
- final - final characteristics</br>

Possible values for the `[parameter_type]` block:
- input - raw material parameters
- output - product parameters
- state - parameters describing the current stage's state
- calculation - calculated characteristics

## Task
Prepare a prototype of a machine learning model for 'Zyfra'. The company develops solutions for the efficient operation of industrial enterprises. The model should predict the gold recovery coefficient from gold-bearing ore.

<a href="https://github.com/DimaDoesCode/Yandex_Practicum-Composite_Project-2/blob/master/composite_project-2/Composite_Project-2_fin.ipynb">To view the Jupyter Notebook code of the research, click on this link.</a>

## Libraries used
<i>catboost, json, matplotlib.pyplot, numpy, pandas, scipy, sklearn, time, warnings</i>