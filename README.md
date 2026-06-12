# Adult Dataset — Data Analysis with Pandas

Hey there! This is my practical project where I practiced data cleaning, filtering, and basic analysis using Pandas. I used the Adult dataset (often called the Census Income dataset) to answer a few interesting questions about people's demographics, education, and salaries.

## What I actually did here:
* **Cleaned up the data:** The original dataset had a bunch of `?` symbols instead of missing values. I replaced them with NaNs and dropped those rows so they wouldn't mess up the statistics.
* **Double-checked the data quality:** I wrote a quick sanity check to make sure that the text salary column (`<=50K` or `>50K`) actually matches the numeric income column. Everything looks correct!
* **Analyzed demographics:** Calculated the gender breakdown, found the average age for men, and looked at how many people in the dataset are from Poland.
* **Explored education and marital status vs. salary:**
  * Checked if there are people making good money (`>50K`) without having a higher education degree.
  * Compared the percentage of high earners among married and unmarried men (turns out, married men in this dataset tend to earn more on average).
* **Looked at working hours:** Found the maximum hours per week someone works and counted how many "hard workers" share that peak schedule.

## How to use it:
Just download the `adult_data_analysis.ipynb` notebook. If you want to rerun the code, make sure you have `pandas` and `numpy` installed, and place the `adult.csv` file in the same folder as the notebook.