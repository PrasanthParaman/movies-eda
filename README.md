# tmdb-movies Data Exploration

## Dataset

The dats consists of information regarding 10866 rows and 21 columns.
After visual and programmatic assessment, the following cleaning actions were done.
	1. Filter the data by removing fields 'id', 'imdb_id', 'original_title', 'homepage', 'tagline', 'keywords', 'overview' from the table
	2. Remove the fields 'budget_adj' and 'revenue_adj' from the table
	3. Remove the single duplicate entry
	4. Remove the rows with null values

After cleaning, the dataset got reduced to 9772 entries and 13 columns.

## Summary of Findings

	1. Animation was most popular in 1960's to 1970
	2. From 1970's to 1980 many genres has been popular. Fantasy, science_fiction and action has made peaks in this region
	3. Animation has made peak again in the late 1980's and early 1990's
	4. Fantasy has been popular from 2000's to 2010
	5. From 2010 onwards, adventure seeems to top the table
## Notes:
	1. Above analysis is applicable only for the shared dataset- tmdb-movies.csv
	2. Only basic statistics have been used to arrive at the above conclusions
	3. The above findings are dervied from only a part of the dataset as many entries were removed due to missing data