## Currently only works with: [Instaffo](https://app.instaffo.com/)

The crawler performs the following steps:
1. Looks for a sitemap.
2. Downloads the sitemap.
3. Searches for a given job title combined with a given date in the sitemap URLs. Then shows only job posts newer than the specified date.

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