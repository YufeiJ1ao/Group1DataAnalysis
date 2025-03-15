# The Rise of Anti-Heroes: A Data-Driven Analysis
**Critical Data Group 1** | 2025 
---
##  Introduction: The Narrative in Data 
In times of upheaval, stories become mirrors through which we perceive the world. Once seen as outliers, have anti-heroes now claimed a new place in the hearts of audiences?  

This project explores the **cultural evolution of anti-heroes**, analyzing over **80,000 social media discussions** across multiple platforms before and after the COVID-19 pandemic.  

Through **sentiment analysis, keyword extraction, topic modeling, and time-series forecasting**, we seek to answer a fundamental question:  
*Has societal change propelled anti-heroes into the mainstream?*  

This is not just an analysis of data but an interpretation of narratives. After the pandemic, we continue searching for heroes, but perhaps our heroes are no longer perfect ideals. Instead, they may be the ones who navigate the gray areas, standing at the crossroads of light and shadow.  

---

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
## Further Reading  
For more details, check out our blog posts:  
- **H1: The Shadow of the Pandemic: The Rise of Anti-Heroes in an Age of Uncertainty**  
  [Read the article](https://criticaldatagroup1.wordpress.com/2025/03/06/the-shadow-of-the-pandemic-the-rise-of-anti-heroes-in-an-age-of-uncertainty/)  
- **H0: The Eternal Gray Area: Why the Pandemic Didn’t Change the Essential Appeal of Anti-Heroes**  
  [Read the article](https://criticaldatagroup1.wordpress.com/2025/03/06/the-eternal-gray-area-why-the-pandemic-didnt-change-the-essential-appeal-of-anti-heroes/)
## References  
Tokgöz, Y. (2016). *The rise of the anti-hero: Pushing network boundaries in the contemporary U.S. television.* Middle East Technical University.  
DiPaolo, M. (2025). *Criminals as Heroes: Problems and Pedagogy in Popular Culture.* Dialogue: The Interdisciplinary Journal of Popular Culture and Pedagogy, 12(1).  
[Anti-Kahraman’ın Soykütüğü] (2025). *A Historical Genealogy of Anti-Heroes.* Ankara University Journal of the Faculty of Languages and History-Geography.  
## About **Critical Data Group 1**  
**Who are we?**  
We are a research team exploring how data can decode cultural narratives. By combining **NLP, statistics, and visualization**, we uncover insights into shifting audience perceptions in digital spaces.
## 👥 Contributors  
Thanks to all the contributors of this project!  
 **Team Members**
- **[Yuf Jiao]** 
- **[SIQI WU]**
- **[JUNJIE LE]**

<a href="https://github.com/YufeiJ1ao/Group1DataAnalysis/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=YufeiJ1ao/Group1DataAnalysis" />
</a>
