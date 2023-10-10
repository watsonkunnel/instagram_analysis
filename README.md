## Instagram Clone Database Analysis & Visualization

## Project Description:
In this project, we analyze an Instagram clone's database to provide insights for marketing purposes and investor metrics. The database schema replicates a simplified version of a social media platform where users can post photos, comment on them, like them, follow other users, and tag photos.

## Approach:
1. **Data Exploration**: Analyzed the database schema to understand relationships between tables and their significance.
2. **SQL Analysis**: Constructed SQL queries tailored to extract the required information for each task.
3. **Visualization with Tableau**: Imported the SQL results into Tableau and created visual representations to highlight patterns and insights.

## Tech-Stack Used:
- **MySQL Workbench**: Used for database management and writing SQL queries.
- **Tableau Desktop**: Used for data visualization, chosen for its intuitive interface and powerful visualization capabilities.

## Data Visualization in Tableau:

### 1. Loyal User Reward:

**Objective**: Reward the most loyal users, i.e., those who have been using the platform for the longest time.

SELECT username, created_at
FROM users
ORDER BY created_at ASC
LIMIT 5;



### 2. Hashtag Research:
Visualize the top 5 most commonly used hashtags.
- Connect to the `tags` and `photo_tags` tables.
- Place `tag_name` on the Rows shelf and count of `tag_id` from `photo_tags` on the Columns shelf.
- Sort by descending count and limit to the top 5 results.

### 3. Ad Campaign Launch:
Visualize user registrations by day of the week.
- Connect to the `users` table.
- In a new worksheet, format `created_at` to display days of the week on the Columns shelf and count of `username` on the Rows shelf.
- Sort days by descending count of registrations.

## Insights:
- **User Engagement**: Discovered patterns in user activity, identifying both highly engaged users and those less active.
- **Content Popularity**: Recognized trends in content preferences, like popular hashtags.
- **Platform Growth**: Understood user registration patterns, aiding in marketing decisions.

## Result:
Through this project:
- We formulated clear strategies for the marketing team using both SQL analysis and visual insights from Tableau.
- Addressed investor concerns with tangible visual data.
- Demonstrated the combination of SQL and Tableau as powerful tools for data-driven decision-making.

## Drive Link:
For a detailed breakdown, code snippets, Tableau workbooks, and a deeper dive into the project, you can access [this Google Drive link](#). (Replace `#` with the actual Google Drive link where you've stored related resources.)

---

You can use this write-up for your GitHub repository. Modify and expand upon it as needed. Best of luck showcasing your work to recruiters!
