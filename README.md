# Netflix Content Analysis & Business Strategy                                                                       



### **Project Overview**
This project analyzes a dataset of movies and TV shows available on Netflix to generate data-driven insights. The goal is to provide strategic recommendations that can help Netflix decide what types of content to produce and how to expand its business in different countries. The analysis focuses on understanding content trends, production years, and popular genres, directors, and actors.


***

### **Business Problem**
The management team at Netflix wants to analyze its content library to answer key business questions. The primary objectives are:

- Which types of movies and shows should Netflix produce to maximize growth?
- How can Netflix grow its business in different countries?


***
### **Dataset**
The analysis is based on the Python Libraries Case Study.csv dataset with the following columns:

| Column | Description |
| :--- | :--- |
| `show_id` | Unique ID for every Movie / Tv Show |
| `type` | Identifier - A Movie or TV Show |
| `title` | Title of the Movie / Tv Show |
| `director` | Director of the Movie |
| `cast` | Actors involved in the movie/show |
| `country` |	Country where the movie/show was produced |
| `date_added` | Date it was added on Netflix |
| `release_year` | Actual Release year of the movie/show |
| `rating` | TV Rating of the movie/show |
| `duration` | Total Duration - in minutes or number of seasons |
| `listed_in` | Genre
| `description` | The summary description

***

### **Methodology and Concepts**
The project follows a structured data analysis pipeline, including:

- **Data Cleaning and Pre-processing:** The data was cleaned to handle missing values and to unnest data from columns like director, cast, and country, which contain multiple values per entry.
- **Exploratory Data Analysis (EDA):** Visual and non-graphical analysis was performed to understand the distribution of content types, genres, release years, and geographical origins.
- **Trend Analysis:** The project tracked the frequency of content releases over time to identify growth patterns and popular launch periods.

***

### **Key Findings and Insights**

### **Observations:**

- **Content Type:** There are significantly more movies than TV shows on the Netflix platform.
- **Production Trend:** The frequency of releasing movies and TV shows has increased gradually from 1940 to 2020, with the highest frequency occurring between the years 2000 and 2020.
- **Geographical Concentration:** The United States is the top country for both movie and TV show production. India is the second-largest producer of movies but ranks seventh for TV shows.
- **Genre Popularity:** International Movies are the most popular genre, followed by Dramas and Comedies.
- **Launch Timing:**
    - The first week of the year is the top week for movie launches.
    - The 27th week of the year is the top week for TV show launches.
    - July is the top month for launching both movies and TV shows.
- **Top Talent:**
    - Rajiv Chilaka and Jan Suter are the top directors with the most credits.
    - Anupam Kher and Shah Rukh Khan are the top actors who have appeared in the most movies/TV shows.

### **Recommendations:**

Based on these insights, here are actionable recommendations for Netflix's business strategy:

1.  **Increase Focus on International Movies:** Since International Movies are the most popular genre, Netflix should invest more in acquiring or producing high-quality content in this category to attract a broader global audience.

2.  **Expand TV Show Production in India:** Given that India is the second-largest movie producer but ranks much lower in TV show production, there is a significant opportunity to grow the business by investing more in Indian TV shows.

3. **Optimize Content Launch Strategy:**
   - Leverage the trend of successful launches in July to release high-profile content during this month.
   - Consider the specific top weeks for movies (Week 1) and TV shows (Week 27) to strategically schedule releases and maximize initial viewership.

4. **Enhance Content Quality:** The analysis suggests that movie ratings are generally higher than TV show ratings. Netflix should focus on improving the quality and curation of both movies and TV shows to enhance customer satisfaction and retention.

### **Technical Skills**

- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn
- **Environment:** Google Colab
- **Repository Link:** `https://github.com/your-username/your-repository-name`

***

### **How to Run the Project**

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ramanujar12-com/netflix_project.git](https://github.com/ramanujar12-com/netfix_project.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd netflix_project
    ```
3.  **Open the Google Colab file (.ipynb):**
    - You can open it directly in Google Colab.
4.  **Install the required libraries (if not already installed):**
    ```bash
    pip install pandas numpy matplotlib seaborn scipy statsmodels
    ```
5.  **Run the notebook cells sequentially** to replicate the analysis and view the results.
