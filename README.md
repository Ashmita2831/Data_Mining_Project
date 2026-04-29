📊 Online Learning Behaviour Analysis using Data Mining (WEKA)
📌 Project Overview
This project focuses on analyzing student behaviour in an online learning environment using data mining techniques. 
The goal is to extract meaningful insights from student activity data such as watch time, quiz performance, login frequency, and course completion.
Using the WEKA tool, various data mining techniques like classification, clustering, association rule mining,
and visualization are applied to understand patterns and improve learning outcomes.

🎯 Objectives
To analyze student interaction data in online learning platforms
To identify factors affecting student performance and engagement
To classify students based on performance categories
To group students based on similar behaviour
To discover hidden relationships between attributes
To visualize important patterns in the dataset

📁 Dataset Description
The dataset contains 50 student records with the following attributes:
Student_ID
Course
Watch_Time
Quiz_Score
Completion_%
Login_Frequency
Drop_Off
Performance Category
Engagement Level
Risk Category

⚙️ Tools & Technologies
WEKA (Waikato Environment for Knowledge Analysis)
Dataset in CSV/ARFF format
Data Mining Techniques

🔄 Methodology
1. Data Preprocessing
Removed unnecessary attribute (Student_ID)
Checked for missing values
Applied Discretization to convert numeric data into categories

2. Classification (Naive Bayes)
Predicts student performance (High/Medium/Low)
Achieved high accuracy (~94%)

3. Clustering (Hierarchical Clustering)
Groups students based on similarity
Identifies different engagement levels

4. Association Rule Mining (Apriori)
Discovers relationships between variables
Sample Rules:
High Quiz Score → High Performance
Low Login Frequency → Drop Off
High Engagement → Low Risk

5. Data Visualization
Scatter plot:
X-axis: Watch_Time
Y-axis: Completion_%
Shows relationship between engagement and completion

📊 Results & Insights
Quiz score is a strong indicator of performance
High engagement leads to better completion rates
Low login frequency increases dropout risk
Watch time positively correlates with course completion

✅ Advantages
Easy to implement using WEKA
No programming required
Provides clear and meaningful insights
Helps in decision-making

⚠️ Limitations
Small dataset size
Results depend on data quality
May not fully represent real-world complexity

🚀 Future Scope
Use larger and real-time datasets
Apply advanced machine learning algorithms
Develop predictive systems for student success
Integrate with real-time dashboards

📌 Conclusion
This project demonstrates how data mining techniques can be used to analyze online learning behaviour effectively. 
The insights obtained can help improve student engagement, reduce dropout rates, and enhance overall learning outcomes.
Or make a DOC/PDF file for submission 👍

