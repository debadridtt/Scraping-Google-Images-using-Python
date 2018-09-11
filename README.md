# Image-Scraping-from-Google-Images
Now  scrape as many images as you want, from google images using Python, Chromdriver and Selenium
**Dependencies needed**
1) `Selenium`
Install as `pip install selenium`
2) [Python 3+](https://www.python.org/download/releases/3.0/?) - Pyhton 3.6+ verion
3) Download `chromedriver.exe`
4) Place your `chromedriver.exe` and `any_image.py` file in the same folder
   > Open your terminal (`cmd` in Windows), change your directory to your Python file location and execute the following query:
     `python any_image.py travel+photos 500`
     travel+photos is equivalent to typing "travel photos" in google images search box, so for spaces put a + and 500 depicts the no. of      images you want to scrape.
     Now in that same directory, you will see a folder `datasets` inside which you will see a folder with the name of search text that you      put in. In my case the folder name will be `travel+photos`.
     P.S. Google search mostly provides a maximum upto 800 photos per search

References: <a href="https://github.com/harshitsidhwa/WhatsApp-bot-selenium">Selenium Installation</a> and <a href="https://github.com/atif93/google_image_downloader">Scraping</a>
