**Titanic Data Analysis Project**

**Introduction:**

This project explores the Titanic dataset from Kaggle, aiming to uncover patterns and factors that influenced passenger survival during the infamous disaster. Through visual and statistical exploration using Python, we analyze demographics, class, cabin decks, family presence, and more to understand who survived — and why.

**Dataset:**

Source: Kaggle Titanic Dataset

File Used: train.csv

Key columns: PassengerId, Survived, Pclass, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

**Key Questions Explored:**

1. Who were the passengers on the Titanic?
→ Explored by age, gender, and passenger class.

2. What deck were the passengers on, and how does that relate to their class?

3. Where did the passengers come from?
→ Based on the embarkation port.

4. Who was alone, and who was with family?

5. What factors helped someone survive the sinking?
→ Investigated survival rates based on age, sex, class, family status, and deck.

**Tools & Libraries:**

•	Python (Pandas, NumPy)
•	Visualization: Matplotlib, Seaborn
•	Jupyter Notebook

**Exploratory Data Analysis:**

1. Demographics of the Passengers:
   
  •	Most passengers were male.
  •	Majority were in 3rd class.
  •	Children were classified based on age < 16.

2. Age Distribution:

  •	KDE plots show age patterns by gender, class, and person type.
  •	Younger passengers had a better survival chance.

3. Cabin Decks:

  •	Decks were extracted from the Cabin column.
  •	Most common decks: B, C, D, E.
  •	Deck T was removed due to being an outlier.

4. Embarkation Points:

  •	Most passengers embarked from Southampton (S).

5. Alone vs With Family:

  •	Derived a new Alone column combining SibSp and Parch.
  •	The majority of passengers were traveling alone.

**Survival Analysis:**

•	Sex: Females had higher survival rates.
•	Class: 1st class passengers had the highest chance of survival.
•	Age: Survival decreased with age.
•	Deck: Decks B, D, and E had higher survival rates.
•	Family: Passengers with family aboard had a better chance of surviving.

**Key Visuals:**

•	Countplots by gender, class, and embarkation.
•	KDE plots for age distributions.
•	Point plots for survival by class, gender, and age.
•	Bar plots showing survival rates by Deck and Family status.

**Insights:**

•	Women and children first was reflected in survival patterns.
•	Class mattered — 1st class passengers had more access to lifeboats.
•	Being with family slightly improved chances of survival.
•	Cabin deck location showed correlation with survival.

**Future Improvements:**

•	Handle missing Age and Cabin values more rigorously.
•	Engineer additional features like Title, Fare per person, etc.
•	Use Machine Learning for predictive modeling.

**Appendix:**

Notebook includes:
  •	Data Cleaning
  •	Feature Engineering (e.g., person, Alone, Deck)
  •	Visual Analysis
  •	Grouped Statistics

**Conclusion:**

This analysis provided valuable insights into survival factors on the Titanic using visual storytelling. It showcases how data can reveal hidden narratives and help simulate real-world data exploration scenarios.
