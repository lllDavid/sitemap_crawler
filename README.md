## Currently only works with: [Instaffo](https://app.instaffo.com/)

The crawler performs the following steps:
1. Looks for a sitemap.
2. Downloads the sitemap.
3. Searches for a given job title combined with a given date in the sitemap URLs. Then filters and retrieves only job posts newer than the specified date.

## Usage 

### 1. Clone the Repository
```bash
git clone https://github.com/lllDavid/sitemap_crawler
```
### 2. Run the Application
```bash
cd sitemap_crawler
python main.py
```
### 3. Options
1. Search for a sitemap, or if already downloaded, directly search by job title.
2. Modify the date variable in job_searcher.py to the desired job posting date.
3. If matches are found, URLs will be printed in the terminal.
