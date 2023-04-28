# Google Search Scraper

This project provides a Python script for scraping Google search results for a given query. The script takes a .tsv file with Google search URLs as input, and outputs the first search result URL for each query.

## Usage

- Create a .tsv file with Google search URLs containing only one query per line.
- Run the google_search_scrapper.ipynb Jupyter Notebook file, which will prompt you to input the path to the .tsv file.
- The script will then iterate through the Google search URLs in the .tsv file, and output the first result URL for each query. 

For example:

```
https://www.google.com/search?q=python+programming
https://www.google.com/search?q=data+science
https://www.google.com/search?q=machine+learning
```

Make sure to save the file with the `.tsv` extension.

## Dependencies

The following libraries are required:

- BeautifulSoup4
- requests
- pandas


## Output

The script will output the first link of each Google search result for each query in the `.tsv` file.

Note that the script only returns the first link of each search result, and will stop searching after finding the first valid link for each query.

