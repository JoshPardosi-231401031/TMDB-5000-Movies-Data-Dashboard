# 🎬 TMDB 5000 Movies Data Analysis & Dashboard

### 📌 Project Description

This is a **beginner-level** data visualization portfolio project built using **Tableau**. Using the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata), the primary goal was to extract meaningful business insights and design an interactive dashboard that highlights:

1.  **Production Trends:** Movie release volume from the 1920s to 2010s.
2.  **Genre Preferences:** Average viewer ratings across different genres.
3.  **Financial Success:** Identifies the top-grossing directors.

---

### 📊 Dashboard Preview

![Dashboard TMDB Preview](dashboard.png)

---

### 🔗 Explore the Project Live

**[>> Click here to view the Interactive Dashboard on Tableau Public <<](https://public.tableau.com/views/Dasbor_TMDB/TMDB5000MoviesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

### 💡 Key Visualizations

The dashboard consists of three primary charts designed to answer specific analytical questions:

*   📈 **Movies Released Over Time:** This visualization utilizes a **chronological line chart** to track the evolution of movie production volume. It reveals a dramatic surge in movie releases starting in the 1990s and peaking in the mid-2000s.

*   📊 **Average Ratings by Genre:** A **bar chart** that compares average viewer ratings across genres. It indicates that while action/adventure genres generate higher revenue (implied from the financial success chart), niche genres like **History, War, and Drama** are consistently rated higher by audiences, demonstrating a preference for narrative depth.

*   🏆 **Top-Grossing Directors:** This chart ranks the top 10 directors by their total cumulative **Gross Revenue**. It uses descending sort and **color gradient** formatting to emphasize the highest earners. Industry titans like **James Cameron and Joss Whedon** dominate this view, showcasing their massive commercial success.

---

### 🛠️ Tools & Techniques

This project serves as a showcase of foundational **data manipulation and storytelling** skills:

*   **Primary Tool:** Tableau Desktop (used for development) / Tableau Public (for deployment).
*   **Data Cleaning:** Addressing complex, nested JSON-like data structures in the 'Genres' and 'Crew' columns.
*   **Data Manipulation:**
    *   **Custom Split:** Extracted clean genre names.
    *   **Calculated Fields (Regex):** Used Regular Expression functions (`REGEXP_EXTRACT`) to isolate and extract the 'Director' name from lengthy text strings.
*   **Filtering:** Applied a 'Top 10' filter to focus on impactful insights.
*   **Visual Design:** Settle axis adjustments, formatting labels (e.g., Hide Field Labels), chronological sorting, and custom color palettes to enhance the data hierarchy.

---

### 📂 Dataset

The **TMDB 5000 Movie Dataset** is a comprehensive metadata repository of thousands of films, including details on budget, revenue, cast, crew, genres, and audience review scores.
