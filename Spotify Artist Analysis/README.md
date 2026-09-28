# Drake Music Analysis

## Project Overview

This project analyzes Drake's music from his debut through 2021 to explore how his albums, tracks, singles, and collaborations performed across different measures of popularity.

The main question was:

> **How does the popularity of Drake's solo releases compare with his features, and are there specific artist collaborations associated with higher popularity?**

The analysis also explores how Drake's music has changed over time, which artists were the most prominent among his collaborations, and whether audio characteristics such as danceability and energy relate to track popularity.

## Questions Explored

- How does the popularity of Drake's solo releases compare with his features?
- Which artists were associated with the most popular Drake features?
- Does danceability or energy appear to relate to track popularity?
- How has Drake's album popularity changed over the years?
- How have Drake's tracks performed on the Billboard Hot 100 over time?
- How do Drake's most and least popular albums compare in terms of track popularity, danceability, and energy?

## Data & Tools

### Data Sources

The analysis used three primary data sources:

- **CSV dataset of Drake's albums and tracks** — including album information, track details, lyrics-related information, and track views.
- **Billboard Hot 100 CSV dataset** — used to examine Drake's chart performance and weeks on the Billboard Hot 100 through 2021.
- **Spotify API** — used to retrieve album and track information, including popularity scores, release years, danceability, and energy.

### Tools & Techniques

- **Python**
- **Pandas** — data cleaning, transformation, filtering, grouping, and analysis
- **Spotify API** — album and track data retrieval
- **Matplotlib & Seaborn** — data visualization
- **Regular Expressions** — artist identification and text filtering
- **Data Aggregation** — calculated metrics including views per featured track

## Analysis

The project combines Spotify API data, Drake track/album datasets, and Billboard Hot 100 data to examine music popularity and collaboration patterns.

- **Album & Track Analysis:** Compared album popularity and examined popularity, danceability, and energy across tracks from Drake's top and bottom albums.
- **Feature Analysis:** Compared featured artists using views per track to account for differences in how frequently artists collaborated with Drake.
- **Billboard Analysis:** Compared Drake's singles and features by year using weeks on the Billboard Hot 100.

## Key Findings

- Drake's album popularity fluctuated over time but remained relatively consistent overall.
- Danceability did **not** show a clear relationship with track popularity in the analyzed data.
- Looking at **views per featured track** provided a different picture than simply comparing total views.
- Kyla and Majid Jordan had the highest views per track among the featured artists analyzed.
- Drake's Billboard performance varied considerably by year.
- In some years, features performed better than singles on the Billboard Hot 100, while in other years the opposite occurred.
- Overall, the analysis did not show an immense difference between Drake's singles and features based on Billboard Hot 100 performance.

## Visualizations

The project uses visualizations to make patterns across Drake's music easier to identify, including:

- Album popularity across release years
- Popularity, danceability, and energy across tracks from selected albums
- Featured-artist comparisons using views per track
- Billboard Hot 100 performance by year
- Comparisons between Drake's singles and features

## What I Learned

This project gave me experience working with multiple data sources and combining them to answer related analytical questions. Rather than relying on a single measure of popularity, I learned how the choice of metric can change the story in the data. The comparison between total views and views per featured track was one example of how a more carefully defined metric can provide additional context.

I also gained experience working with API data, filtering and cleaning real-world datasets, grouping and transforming data with Pandas, and using visualizations to communicate patterns that were difficult to see from raw data alone.

## Future Analysis

A potential next step would be to reverse the perspective and analyze songs where **Drake is the featured artist** on another artist's track. Comparing those results with songs where Drake is the primary artist and another artist is featured could provide additional insight into how Drake's role in a collaboration relates to a track's popularity and other attributes.
