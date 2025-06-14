# Project - YouTube Channel Clustering & Engagement Analysis

This project analyzes YouTube channel performance using clustering techniques and interactive Tableau visualizations. The goal is to identify groups of similar channels based on engagement metrics, helping creators and analysts uncover strategic insights for growth and optimization.

---

## Dataset

The dataset contains YouTube channel and video-level statistics including:

- `channelId`, `videoId`, `videoCategoryId`, `videoPublished`
- Engagement ratios: `likes/views`, `comments/subscriber`, `dislikes/views`, etc.
- Aggregate metrics: `subscriberCount`, `videoViewCount`, `channelViewCount`, `videoCount`

**Source:** Kaggle [Link](https://www.kaggle.com/datasets/thedevastator/youtube-video-and-channel-analytics)

---

## Objective

To segment YouTube channels into clusters using K-means clustering on normalized engagement features. The analysis uncovers behavioral patterns and engagement strategies that differentiate high-performing channels from the rest.

---

## Methodology

### 1. **Feature Engineering**
Created engagement-based ratios:
- `likes/views`, `comments/subscriber`, `dislikes/views`, `views/subscribers`
- Time-based metrics like `views/elapsedtime`, `totalviews/channelelapsedtime`

### 2. **Data Preprocessing**
- Removed duplicates and nulls
- Standardized numerical features for clustering

### 3. **Clustering**
- Used **K-means** clustering (tested K = 2 to 6)
- Chose optimal K using **Elbow Method** and interpretability

### 4. **Visualization**
- Built interactive dashboards in **Tableau** to analyze:
  - Cluster profiles
  - Engagement by video category
  - Distribution of likes, comments, and views per cluster

---

## Key Insights

- Channels in **Cluster 0** had high engagement but moderate view counts — ideal for brand engagement.
- **Cluster 2** channels dominated in volume but underperformed in subscriber interaction — indicating mass content with low loyalty.
- Certain categories like *Gaming* and *Education* consistently clustered in high-engagement groups.


---

## Tools Used

- Python (Pandas, Scikit-learn, Seaborn for exploration)
- Tableau (Dashboard and cluster analysis)
- K-Means Clustering
- Jupyter Notebook (Optional for preprocessing)

---

## Tableau Dashboard

Tableau Visualization: [Link](https://public.tableau.com/app/profile/anubhavdogra/viz/YouTube-Channel-Clustering---Engagement-Analysis/YouTubeClusterDashboard)

---

# Contact
- Email: [anubhavdogra7@gmail.com](mailto:anubhavdogra7@gmail.com)
- LinkedIn: [linkedin.com/in/anubhav-dogra](https://www.linkedin.com/in/anubhav-dogra/)
- GitHub: [github.com/anubhavdogra1](https://github.com/anubhavdogra1)
- Instagram: [@anubhavdogra1](https://www.instagram.com/anubhavdogra1/)
- Website: [My Portfolio](https://fuschia-yak-f61.notion.site/Anubhav-Dogra-211d6dc537bf8027bfe3ebdf322032ec)

