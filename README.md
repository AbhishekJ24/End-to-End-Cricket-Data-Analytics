# End-to-End Cricket Data Analytics

This project aims to perform end-to-end data analytics on cricket data, including data collection, preprocessing, visualization, and analysis.

### Data Collection

We use Bright Data for scraping cricket data from ESPN Cricinfo. The data collection is divided into stages:

- Match Results Scraping: Collects match results data.
- Batting Summary Scraping: Gathers batting statistics for players.
- Player Information Scraping: Retrieves player information.

### Data Preprocessing

After collecting the data, we preprocess it using Python scripts:

- Match Results Processing: Processes and stores match results data in CSV format.
- Batting Summary Processing: Processes and stores batting statistics in CSV format.
- Player Information Processing: Processes and stores player information in CSV format.

### Data Visualization and Analysis

We analyze the collected data to gain insights into top performers:

- Top Batsmen Analysis: Visualizes and analyzes top batsmen based on runs scored.
- Top Bowlers Analysis: Visualizes and analyzes top bowlers based on wickets taken.

### Project Structure

- Bright Data Scraping Scripts: Contains Bright Data scraping scripts for each stage.
- Scraped Data: Stores scraped JSON files and processed CSV files.
- Visualization and Interpretations: Includes visualizations generated from the data analysis and the respective interpretations.

### Usage

- Clone the repository: git clone [https://github.com/AbhishekJ24/end-to-end-cricket-analytics.git](https://github.com/AbhishekJ24/End-to-End-Cricket-Data-Analytics.git)
- Install the required dependencies.
- Run the scraping scripts to collect data.
- Run the preprocessing scripts to process the data.
- Use the analysis scripts to visualize and analyze the data.

### Dependencies

- Bright Data (for scraping)
- Python 3.x
- Pandas
- Matplotlib

### Contributing

Contributions are welcome! Please open an issue or submit a pull request with your suggestions or improvements.
License
