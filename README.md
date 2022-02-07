# OTC CatchUp Dashboard
<p>A Power BI dashboard analyzing OTC CatchUps.</p>

## File Contents
- OTC scraper.ipynb - Code to scrape OTC catchup summaries from CatchUp #54 available on the [OTC website](https://catchup.ourtech.community/summary).
- data folder - Contains markdown files of CatchUp summaries starting from CatchUp #11 to CatchUp #53 with a few missing.
- old otcs.ipynb - Code to extract relevant data from the summaries and saving it to  old_otcs.csv
- data cleaning.ipynb - Code to merge the csv files and get all the columns in the right format for visualization.

## Results
<p align="center">
  <img src="result.png" alt="result" width="80%" />
</p>

Note: The data regarding attendees consists of data from OTC CatchUp #54 to CatchUp #63 only.

Special mentions to [Dheeraj Lalwani](https://github.com/dheerajdlalwani) for providing the data for CatchUp #11 to CatchUp #53 summaries.

You can find the dashboard [here](https://mihikagaonkar.github.io/OTC-Dashboard/)