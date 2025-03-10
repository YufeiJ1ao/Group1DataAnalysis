# Group1DataAnalysis
## Group 1 Data Representation, Analysis and Visualisation
In times of upheaval, stories become mirrors through which we perceive the world. Once seen as outliers, have antiheroes now claimed a new place in the hearts of audiences? Using data as our guide, we trace the emotional undercurrents before and after the pandemic to uncover the evolving perception of antihero figures in collective consciousness.

We believe that data is more than just numbers—it is the imprint of emotions. Through sentiment analysis, keyword extraction, topic modeling, and time-series forecasting, we seek to answer a fundamental question: Has societal change propelled antiheroes into the mainstream?

This is not just an analysis of data but an interpretation of narratives. After the pandemic, we continue searching for heroes, but perhaps our heroes are no longer perfect ideals. Instead, they may be the ones who navigate the gray areas, standing at the crossroads of light and shadow.
###
##

### [dataSet1: Bilibili & Weibo comment sentiment](https://github.com/YufeiJ1ao/Group1DataAnalysis/tree/main/dataSet1)
#### Bilibili
Extracted bullet comments (Danmu) and text-based comments from high-engagement videos.
Comments were filtered based on word count (longer responses preferred) and engagement metrics (high likes/upvotes) to ensure high-quality discussions.
#### Weibo
Collected posts and comments from trending topics related to each character.
Posts were selected based on engagement levels (likes, reposts, and comment counts).
### [dataSet2: Douban discussion sentiment](https://github.com/YufeiJ1ao/Group1DataAnalysis/tree/main/dataset2)
#### Douban
Data from the short review pages of “Attack on Titan” Seasons 1, 2, and 3, “Ne Zha: Birth of the Demon Child“, “Ne Zha 2 “, and “Final Fantasy VII: Advent Children” were collected. And conduct an analysis of the positive sentiment of the data containing evaluations related to anti-hero characters (Shen Gongbao, Sephiroth, Eren Yeager).

The dataset contains 400 positive, 400 medium, and 400 negative reviews for each movie page, totaling approximately 7,200 pieces of data.
### [dataSet3: Reddit comment sentiment](https://github.com/YufeiJ1ao/Group1DataAnalysis/tree/main/dataSet3)
#### Reddit
Data from the subreddit tags under anti-hero, collected comments and discussions. Scraped text were filtered based on sentiment word.

### **Analysis Structure Overview**
Each dataset includes its own independent analysis, focusing on platform-specific sentiment trends.
The final section at the bottom provides a comprehensive joint analysis combining all datasets for a broader perspective.

### [Three dataSets merged and analysis](https://github.com/YufeiJ1ao/Group1DataAnalysis/blob/main/Three%20datasets%20analysis.ipynb)
This Jupyter Notebook contains the full pipeline for analyzing sentiment trends in audience perception of antiheroes before and after the COVID-19 pandemic. The analysis is based on three datasets from Bilibili, Weibo, Douban and Reddit.

This notebook serves as a comprehensive analysis tool ，applying Mann-Whitney U Test, Kolmogorov-Smirnov Test, Chi-Square Test, and effect size calculations (Cliff’s Delta, Hedges’ g) to assess sentiment shifts."

### [Extra analysis](https://github.com/YufeiJ1ao/Group1DataAnalysis/blob/main/Analysis%20of%20Different%20Platforms.ipynb)
During the process of writing the report, more visualizations are needed.
---
## Anti-Hero Sentiment DNA Visualization

An interactive 3D data visualization illustrating the evolution of public sentiment toward anti-hero characters.

### Live Visualization
 [Click here to view](https://group1-antihero.netlify.app/)
 *The visualization may take a few seconds to load. Please be patient.* 
### Features
- **3D DNA Structure:** A visual representation of sentiment evolution over time.
  - **Red** - Strong emotions (highly positive or extreme reactions)
  - **Gold** - Neutral or middle-ground views
  - **Green** - Negative or critical opinions
- **Interactive Controls:**
  - Click on a node to reveal public opinions at that point in time.
  - Adjust rotation speed for customized viewing.
  - Zoom and drag to explore different perspectives.
---
