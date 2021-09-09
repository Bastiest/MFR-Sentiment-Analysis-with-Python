# MARVEL Future Revolution
Exploring MARVEL Future Revolution (MFR) reviews: A Rule based Sentiment Analysis
![image](https://user-images.githubusercontent.com/78896519/132472135-721e9e46-a82f-4186-9240-86372b9581a9.png)

## App Information
<b> Release Date: </b> August 25, 2021
<br>
<b> Developer: </b> Netmarble Monster
<br>
<b>Publisher:</b> Netmarble
<br>
<b> Genre: </b> Open-World Action RPG
<br>
<b>Current Version:</b> 1.1.5
<br>
<b> Platform: </b> iOS / Android
<br>
<b>Size:</b> 1.6G

## Overview
MARVEL Future Revolution is Marvel’s first Open World Action RPG mobile game. As members of the ‘Omega Flight’ team, players will work together to battle an onslaught of Super Villains, confront their nefarious behaviors and defend the universe.
https://www.marvelfuturerevolution.com/en/?referrer=singular_click_id%3Dcf5c1935-6d35-463d-8d56-fddeaacd76d1

## Methods
<b>1. Data collection procedure, sample size, and sampling design</b>
<br>
The MFR data were collected, processed, and analyzed using Python through Jupyter Notebook.
Reviews was collected using a library like Google-Play-Scraper (https://github.com/JoMingyu/google-play-scraper). There is a total of 104,356 reviews, 
only 16,363 was collected.
<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132649738-151eb322-4ff9-4006-b958-c1d294d1658e.png" />
</p>
<br>
<b>2. Data cleaning and data preprocessing</b>

Data cleaning and preprocessing were performed to the collected reviews. Next, the reviews were tokenized
and transformed into lower case. Punctuation marks (e.g., “!”, “?”, etc.), special characters, and
numbers were also removed, and then followed by the application of word stemming. Afterwards,
a list of English stop words from the Natural Language Toolkit (NLTK) library was used
to filter unnecessary texts (e.g., and, the, a, etc.) from the reviews.
<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132650327-d3f1880a-aea4-417f-b69f-9c07736bd9e8.png" />
  <img src="https://user-images.githubusercontent.com/78896519/132650522-cb0b9966-79ac-413c-8b88-63cad6a34766.png" />
</p>
<br>
<b>3. Data analysis</b>

Used a rule based sentiment analysis approach to analyzing text without training or using machine learning models. The result of this approach is a set of rules based on which the text is labeled as positive/negative/neutral. These rules are also known as lexicons. Hence, the Rule-based approach is called Lexicon based approach.

<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132651056-243226e7-dc79-45bc-978e-b7cca63e0b84.png" />
</p>

### Positive frequency wordcloud
<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132651285-a81ca73c-ebaf-48de-bc86-69bc5e998e2d.png" />
</p>
<br>

### top 10 frequency 
<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132651402-28342285-b273-4512-81d1-a3b47d7cc45a.png" />
</p>
<br>

### sample content
<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132651715-fd5a2483-cc47-4c63-ad26-7287ed267c79.png" />
</p>
<br>

### Negative frequency wordcloud
<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132652037-ed213a35-d0bf-41bd-85df-296d01d6fe9d.png" />
</p>
<br>

### top 10 frequency 
<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132652113-1313132c-adac-4e89-83b0-5b3addddc301.png" />
</p>
<br>

### sample content
<p align="center">
  <img src="https://user-images.githubusercontent.com/78896519/132652212-0a0dd72b-1ed8-4de7-9e23-0319ae023bc6.png" />
</p>
<br>




















