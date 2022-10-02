# Image Scraper  
An image scraping script using python. In layman's term, a google image downloader script.
## Prerequisites:
- should have python installed from [here](https://www.python.org/downloads/)
- should have pillow, requests, and selenium installed (steps provided below)
- should have the latest Chrome version up and running
## Steps:
- if you are on windows, open command prompt and type the following commands to install the packages listed below:

```pip install Pillow```

```pip install requests```

```pip install selenium```
- make sure you have the latest chrome driver from [here](https://chromedriver.chromium.org/home)
- extract the zip file inside the chromedriver directory provided in the repo (by default there should be a default file provided, replace that with the extracted file)
## How to use:
- google what you want to download
- go the the images tab and copy the link in the search bar
- run the script
- paste the link
- enter the number of images you want
- script does the job
## Note
- before re-running the script to download new images, make sure you have the previous images moved to a different file location from the 'images' directory created as a re-run will overwrite the old contents
