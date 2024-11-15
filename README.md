# mars_M11_challenge


# Module 11 Challenge: Mars News and Weather Data

## Overview

This project involves web scraping and data analysis tasks to explore Mars-related data from two sources:

1. Mars news articles (titles and previews).
2. Mars weather data (temperature and atmospheric pressure).

The project demonstrates scraping web pages using **Splinter** and  **BeautifulSoup** , organizing the data into appropriate formats, and performing analysis with **Pandas** and  **Matplotlib** .

---

## Deliverables

1. **Scrape Titles and Preview Text from Mars News** :

* Automated browsing using Splinter to visit the Mars News website.
* Scraped and stored titles and previews of articles in a Python list of dictionaries.

1. **Scrape and Analyze Mars Weather Data** :

* Scraped a table of Mars weather data using BeautifulSoup.
* Converted the data into a Pandas DataFrame and analyzed it.
* Visualized key metrics such as average temperature and pressure by month.

---

## Files in Repository

* `part_1_mars_news.ipynb`: Jupyter Notebook for scraping Mars news titles and previews.
* `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analyzing Mars weather data.
* `mars_weather.csv`: Cleaned Mars weather data exported to a CSV file.
* `mars_news.json`: Scraped Mars news data exported to a JSON file.

---

## Tools and Libraries Used

1. **Python Libraries** :

* `Splinter`: For browser automation to visit and interact with web pages.
* `BeautifulSoup`: For parsing HTML and extracting data elements.
* `Pandas`: For data organization, cleaning, and analysis.
* `Matplotlib`: For creating visualizations.

1. **Jupyter Notebook** : For iterative development and analysis.

---

## Analysis Highlights

### **Mars News**

* Scraped and stored 15 recent Mars news articles, including titles and previews.
* Example:
  <pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary select-none">json</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center select-none py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-json">{
    "title": "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
    "preview": "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."
  }
  </code></div></div></pre>

### **Mars Weather**

* Scraped weather data spanning 1867 Martian sols (days).
* Cleaned and analyzed columns such as:
  * Minimum temperature.
  * Atmospheric pressure.
  * Terrestrial date and Martian months.

 **Key Findings** :

1. Coldest month: **Month 3** (average minimum temperature:  **-83.31°C** ).
2. Warmest month: **Month 8** (average minimum temperature:  **-68.38°C** ).
3. Lowest pressure: **Month 6** (average pressure:  **745.05 Pa** ).
4. Highest pressure: **Month 9** (average pressure:  **913.31 Pa** ).

---

## Visualizations

1. **Average Minimum Temperature by Month** :
2. **Average Atmospheric Pressure by Month** :
3. **Daily Minimum Temperature Across Sols** :

---

## External Resources Used

1. **Splinter Documentation** :

* [https://splinter.readthedocs.io/](https://splinter.readthedocs.io/)

1. **BeautifulSoup Documentation** :

* [https://www.crummy.com/software/BeautifulSoup/bs4/doc/]()

1. **Pandas Documentation** :

* [https://pandas.pydata.org/](https://pandas.pydata.org/)

1. **Matplotlib Documentation** :

* [https://matplotlib.org/stable/contents.html]()

1. **USGS Mars Data** :

* Mars Weather Data: [https://static.bc-edx.com/data/web/mars_facts/temperature.html](https://static.bc-edx.com/data/web/mars_facts/temperature.html)
* Mars News Articles: [https://static.bc-edx.com/data/web/mars_news/index.html](https://static.bc-edx.com/data/web/mars_news/index.html)

1. **Stack Overflow** :

* Used for resolving Splinter and BeautifulSoup-related issues.

---

## How to Use

1. Clone this repository:
   <pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary select-none">bash</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center select-none py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-bash">git clone https://github.com/your-username/module-11-mars-challenge.git
   </code></div></div></pre>
2. Open `part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb` in Jupyter Notebook or Jupyter Lab.
3. Run the notebooks to scrape and analyze the data.
4. View the exported files (`mars_news.json` and `mars_weather.csv`).

---

## Acknowledgments

This project is part of the  **University of Toronto Data Analytics Bootcamp** . The Mars data and web pages are used for educational purposes.
