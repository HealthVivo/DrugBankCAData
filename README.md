# Drugbank Crawler

This repository contains the drug images crawled from 
[Drugbank](https://www.drugbank.ca/)

## How to run 

1. Install Jupyter Notebook using [Anaconda](https://www.anaconda.com/) or from anyother source
2. Ensure you have Python 3 installed
3. Start the notebook using the command `jupyter notebook` in the current folder
4. Ensure that following packages are installed
    1. svglib
    2. reportlab
    3. scrapy
    4. urllib
    5. requests
    6. pathlib
5. Open Drugbank_Crawler.ipynb and execute all the cells - This will crawl all the data from drugbank and store the images in the `svg` folder in .svg format
6. Open PNG_Convert.ipynb and execute all the cells - This will use the `svg` folder to convert it into .png images and store it in `png` folder inside the same directory. This will also remove images containing `No Structures Found`
7. You will have all the images in the `png` folder

## Here are the classes and count of the crawled data:

|Classes                | Count|
|:---------------------:|:----:|
|cardiovascular         |419   |
|central nervous system |963   |
|anti-infective         |671   |
|gastrointestinal       |209   |
|anti-inflammatory      |233   |
|dermatological         |85    |
|hematologic            |111   |
|lipid regulating       |49    |
|reproductive control   |70    |
|respiratory system     |112   |
|urological             |21    |
|antineoplastic         |494   |


