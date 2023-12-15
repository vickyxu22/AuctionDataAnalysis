# Auction Data Analysis

## Project Overview

The `AuctionDataAnalysis` class is used for preprocessing auction records and generating a data analysis report to facilitate understanding trends and data patterns within the auction records.

### Class Methods:
1. `__init__(file_path)`: Initializes the class with the specified dataset file path.
2. `preprocess_data()`: Preprocesses the dataset, including standardizing price formats and organizing movement orders.
3. `get_author_name()`: Retrieves the name of the report's author.
4. `get_record_num()`: Provides the count of auction records in the dataset.
5. `get_top_artists()`: Presents the total count of unique artists and lists the top ten contributing artists.
6. `get_top_titles()`: Displays the count of unique titles and highlights the most frequent five titles in the dataset.
7. `visualize_period_statistics()`: Generates a table detailing the Combined Price Statistics for Each Period (sorted in descending order by counts) and provides visual insights into Mean Price and Counts for Each Period.
8. `visualize_movement_statistics()`: Produces a table outlining the Combined Price Statistics for Each Movement (sorted in ascending order based on the historical timeline of movements) and showcases Mean Price and Counts for Each Movement.

### Additional Information:
The file includes an appendix explaining the Historical Timeline of Movements.

### Dataset Information:
The class is tested using the Sotheby's art price dataset from Kaggle.

Citation:
Fl.Kuhm. (2022). Art Price Dataset [Dataset]. Kaggle. DOI

The dataset comprises artworks and sculptures listed for sale on Sothebys, encompassing artist names, prices, associated time periods, and art movements.
