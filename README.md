# 📊 Netflix Movies and TV Shows Data Analysis using SQL

![netflix-images-for-subtitles-and-captions](https://github.com/user-attachments/assets/4042fb23-568b-4a1f-99c2-cf12db6e5908)

This project presents a comprehensive analysis of Netflix's Movies and TV Shows dataset using SQL. The objective is to explore content distribution, ratings, trends over the years, and other insights to inform content strategy and viewer preferences.

---

## 🗃 Dataset Structure

The dataset includes the following columns:

- `show_id`: Unique identifier for the show  
- `type`: Movie or TV Show  
- `title`: Title of the content  
- `director`: Director's name  
- `casts`: List of cast members  
- `country`: Country of origin  
- `date_added`: Date added to Netflix  
- `release_year`: Year of release  
- `rating`: Content rating (e.g., TV-MA, PG)  
- `duration`: Runtime or number of seasons  
- `listed_in`: Genres  
- `description`: Content synopsis  

---

## 📌 Business Problems and SQL Solutions

| No. | Problem Statement                                                                 | Objective                                                                 |
|-----|------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| 1   | Count the number of Movies vs TV Shows                                            | Understand content distribution by type                                   |
| 2   | Find the most common rating for Movies and TV Shows                               | Identify frequently assigned ratings                                      |
| 3   | List all movies released in a specific year (e.g., 2020)                          | Retrieve time-specific content                                            |
| 4   | Top 5 countries with the most content on Netflix                                   | Understand geographical content spread                                    |
| 5   | Identify the longest movie                                                        | Find the movie with the longest runtime                                   |
| 6   | Find content added in the last 5 years                                            | Analyze recent content additions                                          |
| 7   | Find all content by director 'Rajiv Chilaka'                                      | Filter content by a specific director                                     |
| 8   | List all TV shows with more than 5 seasons                                        | Identify long-running TV shows                                            |
| 9   | Count the number of content items in each genre                                   | Understand genre distribution                                             |
| 10  | Top 5 years with highest average content releases from India                      | Discover trends in Indian content release                                 |
| 11  | List all documentaries                                                            | Filter content labeled as "Documentaries"                                 |
| 12  | Find all content without a director                                               | Identify incomplete or missing metadata                                   |
| 13  | Count movies with 'Salman Khan' in the last 10 years                              | Track an actor's recent work on the platform                              |
| 14  | Top 10 actors in Indian-produced content                                           | Analyze top recurring actors                                              |
| 15  | Categorize content based on presence of "kill" or "violence" in description       | Perform sentiment-based categorization                                    |

---

## 🔍 Key Findings and Insights

- **Content Distribution**: Balanced mix of Movies and TV Shows with varied durations and genres.
- **Ratings Analysis**: PG-13, TV-MA, and TV-14 are among the most frequently used ratings.
- **Top Producing Countries**: USA and India dominate the content production on Netflix.
- **Trending Years**: Certain years show spikes in content release, particularly for Indian content.
- **Content Categorization**: Descriptions containing terms like "kill" or "violence" were flagged, helping in sentiment-based content tagging.
- **Actors & Directors**: Top actors and notable directors (like Rajiv Chilaka) were identified through cast/director analysis.

---

## 💻 Tools Used

- **SQL (PostgreSQL)**: Querying and data analysis  
- **Jupyter Notebook / pgAdmin**: For running SQL queries and visual inspection  
- **GitHub**: Version control and project sharing  

---

## 📂 Folder Structure
netflix-sql-analysis/
│
├── queries.sql           # All SQL queries used in the analysis
├── netflix_schema.sql    # Table creation script
├── dataset.csv           # Original Netflix dataset
├── README.md             # Project documentation


---

## 📌 How to Run

1. Import the `dataset.csv` into your local PostgreSQL database.
2. Execute the `netflix_schema.sql` to create the table.
3. Run the queries from `queries.sql` to generate the analysis.

---

## 🧠 Conclusion

This project provides actionable insights into Netflix’s content library using SQL, highlighting trends, metadata gaps, and genre diversity. It can assist media analysts, content strategists, and data enthusiasts in better understanding viewer preferences and platform trends.
