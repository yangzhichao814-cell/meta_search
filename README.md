## meta_search

**Author:** yzc
**Version:** 0.0.1
**Type:** tool

### Description
A meta search plugin that allows users to search for articles by keywords. This tool aggregates results from multiple sources to provide comprehensive search results.

### Parameters
- `keyword`: Search keyword or phrase (required)

### Output
Returns a list of articles with the following information:
- Title
- URL
- Summary/Abstract
- Source
- Published date

### Usage
To use this tool, simply provide a search keyword. The tool will return relevant articles from various sources based on your keyword.

Example:
{
  "keyword": "artificial intelligence"
}

### Requirements
- Python 3.6+
- requests library
- BeautifulSoup4

### Installation
Clone the repository and install required dependencies:
pip install -r requirements.txt

### Configuration
No additional configuration needed for basic usage.



