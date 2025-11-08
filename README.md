# 🎧 Spotify & YouTube Dataset — EDA

This project performs an **Exploratory Data Analysis (EDA)** on a dataset combining Spotify and YouTube music data.
It explores trends in **artist**, **track**, and **channel performance**, along with relationships between **audio features and engagement metrics**.

### 📊 Key Steps

**1. Data Cleaning**
* Removed unnecessary columns (URLs, descriptions, etc.)
* Filled missing Likes and Comments with 0
* Dropped remaining null rows

**2. Feature Exploration**
* Checked dataset structure, shape, and unique values
* Summarized main statistics using .describe() and .info()

**3. Visual Analysis**
* Top 10 channels, artists, and tracks by Views, Likes, and Streams
* Engagement comparison by Album Type
* Histograms & Boxplots for numeric features
* Correlation Heatmap of audio and engagement metrics

### 🧠 Insights

* Top-performing artists and tracks can be identified from YouTube and Spotify data.
* Album type and danceability show notable variation in engagement.
* Correlation matrix helps reveal which features impact popularity.
