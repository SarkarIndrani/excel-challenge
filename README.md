# excel-challenge
## Background
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdunding to launch new products and generate buzz, but not every project has found success.
To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate condiderable resources looking through this Challenge, I was asked to organize and analyze a database of 1,000 sample projects to uncover any hidden trends.

## Procedure:
![](./Images/outcome.PNG)
Using the Excel workbook in my .zip file, modify and analyze the sample-project data and try to uncover market trends.
* Data for this dataset was generated by edX Boot Camps LLC, and is intended for educaitonal purpose only.
* Use conditional formatting to fill each cell in the `outcome` column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
  * Create a new column called `Percent Funded` that uses a formula to find how much money a campaing made relative to its initial funding goal.
* Use conditional formatting to fill each cell in the `Percent Funded` column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.
  * Create a mew column called `Average donationo` that uses a formula to find how much each project backer paid on average.
  * Create two new columns, one called `Parent Category` and another called `Sub-Category`, that use formulas to split the `Category and Sub-Category` column into the two new, separate columns:

    ![](./Images/pivot.png)

  * Create a new sheet with a pivot table that analyses my initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

 * Create a stacked-column pivot chart that can be filtered by country based on the table I created.
   
