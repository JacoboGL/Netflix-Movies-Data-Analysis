# Project Overview

See the complete project and code in nbviewer:
[Netflix Movies Data Analysis](https://nbviewer.org/github/JacoboGL/Netflix-Movies-Data-Analysis/blob/master/Netflix_Movies_Data_Exploration.ipynb)

This project performs an end-to-end Exploratory Data Analysis (EDA) on the Netflix dataset to uncover content trends, global production hubs, and shifts in viewer preferences over the decades.

The dataset is currently stored in the netflix_data.csv database, and its structure is as follows:

### Dataset structure
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

# Netflix Content Addition Strategy:

**Key Insight**: Since 2015, Netflix has significantly ramped up its library. While Movies still hold the highest total count, the growth rate of TV Shows has outpaced movies in recent years.

**Analysis**: This suggests a strategic shift toward episodic content, which typically yields higher user retention and "binge-watching" behavior compared to one-off films.

![Netflix Growth Trend](https://i.imgur.com/kqJqayH.png)

# Global Footprint:

**Key Insight**: The United States remains the dominant content producer, followed closely by India.

**Analysis**: The high volume of Indian content indicates Netflix's heavy investment in the South Asian market. European hubs like the UK and Spain also show strong presence, highlighting the platform's "Global Originals" strategy to capture local markets and export them worldwide (e.g., Money Heist).

![Top 10 Countries by Content](https://i.imgur.com/z5IAJH7.png)

# Movie Duration:

**Key Insight**: By analyzing the distribution of movie lengths by decade, we see that the median duration for movies has slightly decreased since the 1990s.

**Analysis**: Modern movies (2010s-2020s) show a tighter distribution around the 90–100 minute mark, likely catering to the shrinking attention spans of digital-first audiences, whereas older decades had a wider variance in bigger lengths.

![Distribution of movies and series duration](https://i.imgur.com/Au4kGi0.png)

# Content Hierarchy: A Deep Dive into Genres

**Key Insight**: The platform’s library is anchored by Dramas and Comedies in the Movie sector, while TV Shows are heavily dominated by International TV and Crime/Docuseries.

**Analysis**: This distribution reflects a "Global-Local" strategy. By focusing on "International TV," Netflix creates low-cost, high-engagement local content that can be exported globally (like Squid Game or Money Heist), while maintaining a massive volume of "comfort" genres like Comedies to ensure high daily active usage.

![Content Hierarchy](https://i.imgur.com/oIqq2Ei.png)

# Seasonality:

**Key Insight**: The heatmap reveals a consistent trend: Netflix adds a massive volume of content in January and December.

**Analysis**: This aligns with peak holiday viewership. By dropping high-profile "Originals" during the winter break, Netflix maximizes its "hours watched" metric when global audiences have the most free time.

![Seasonality Heatmap](https://i.imgur.com/Amr2os4.png)

# Cast Analysis:

**Key Insight**: The list of most frequent actors is dominated by Indian cinema legends such as Anupam Kher and Shah Rukh Khan.

**Analysis**: This data reveals a "hidden" side of the platform—Netflix is not just a Hollywood library; it is arguably one of the largest distributors of Bollywood content in the world, serving a massive global diaspora.

![Cast Analysis](https://i.imgur.com/rjp3w4J.png)

# Thematic Word Cloud: Common Narratives

**Key Insight**: The most frequent words in descriptions include "Family," "Life," "Find," "World," and "Love."

**Analysis**: Netflix content focuses heavily on universal human experiences. The prominence of "Family" and "Friend" suggests a strong focus on "four-quadrant" content—shows that appeal to kids, teens, and adults simultaneously.

![Common Narratives Word Cloud](https://i.imgur.com/X4MxJgA.png)
