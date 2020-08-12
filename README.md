# Image-Scraping-from-Google-Images
Now  scrape as many images as you want, from google images using Python, Chromdriver and Selenium
**Dependencies needed**
1) `Selenium`
Install as `pip install selenium`
2) [Python 3+](https://www.python.org/download/releases/3.0/?) - Pyhton 3.6+ verion
3) Download `chromedriver.exe`
4) Place your `chromedriver.exe` and `google_image_scraping_script.py` file in the same folder

The `error_clicks` parameter is to stop when there are no more results to show and end of the page is reached in Google Images search.

Line 99 change the queries you want to search: `queries = ["Manchester City", "Manchester United", 'Barcelona', 'Real Madrid']` in my case

Line 104 `links = fetch_image_urls(query,500,wd)`, 500 denotes no. of images you want to download
   > Open your terminal (`cmd` in Windows), change your directory to your Python file location and execute the following query:
     `python google_image_scraping_script.py`
     Now in that same directory, you will see a folder `datasets` inside which you will see a folder for each name of search text that you put in. In my case the folder names will be the list of queries that I have passed.

It is recommended to keep your machine idle while the scraping script is running end-to-end.

References: https://medium.com/@wwwanandsuresh/web-scraping-images-from-google-9084545808a2
