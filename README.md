# county-plans
Project to assess county plans related to covid.
***R Persichitte<br>7/25/2020***

## Purpose:
The purpose of this repository is to create a working model to assess the quality of countywide plans and orders related to COVID. To achieve this goal, I will perform the following steps:
- 1) Scrape information about counties and their plans related to COVID. Use OCR to extract information about the various plans including:
  - How strong the language is (e.g. should vs. shall)
  - Mention of fines or penalities
  - Length of plan
  - Publication date of plan
- 2) Create a working model to predict the number of COVID cases. This model will include:
  - Information about county plans including if a written plan is availiable and the strength of the language.
  - Publicly availiable information such as population, population density, age demographics, and income demographics.
  - To account for reporting differences, I will also include state as a variable, this will hopefully account for differences in how state measure COVID cases.
  - I will experiement with one other variable which is political affiliation. I believe that COVID and a community's reaction to it have been politicized and may yield interesting results.
- 3) Use residual analysis to dermine which plans are effective, then use machine learning to determine which plan elements are the most effective.
