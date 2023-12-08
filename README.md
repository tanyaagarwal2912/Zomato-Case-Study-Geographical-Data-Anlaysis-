# Zomato-Case-Study-Geographical-Data-Anlaysis-

Welcome to the Zomato Case Study project repository! This project serves as a comprehensive guide in data analysis using Python, NumPy, Pandas, Matplotlib, Seaborn, and other essential packages. Let's dive into the world of data analysis and gain valuable insights from Zomato's restaurant data.

Project Overview:

1. How to Read Data Using SQLite3:
Create a SQL connection to the SQLite database.
Read data from the "Users" table into a Pandas DataFrame.

con = sqlite3.connect(r"zomato_rawdata.sqlite")
df = pd.read_sql_query("SELECT * FROM Users", con)

2. Dealing with Missing Values:   
Understand the importance of handling missing values.
Learn strategies for dealing with missing data depending on the problem statement.

3. Relation between Online Order Option and Restaurant Rating:
Explore the relationship between restaurant ratings and online order acceptance.
Create frequency tables to analyze ratings based on the online order option.

4. Data Cleaning for Text Analysis:
Perform text analysis on customer reviews for various restaurants.
Use word clouds and charts to gain insights from customer feedback.

5. Performing Unigram Analysis and Removal of Stopwords:
   
Analyze individual word frequencies in customer reviews.
Remove stopwords and store data for further analysis.

6. Performing Bi-gram and Trigram Analysis:
Analyze bigrams and trigrams to discover insights.
Gain a deeper understanding of customer preferences and factors contributing to restaurant experience.

7. Extracting Geographical Coordinates:
Extract latitude and longitude data for restaurants using Nominatim.

8. Building Geographical Heat-Maps:
Visualize the geographical distribution of restaurants in Bengaluru using heat-maps.

9. Automation of Analysis:
Design a function for automating repetitive analysis tasks.
Enhance efficiency by automating data analysis processes.
