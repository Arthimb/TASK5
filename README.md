# TASK5
This project performs exploratory data analysis (EDA) on the Titanic dataset using Python libraries like Seaborn and Matplotlib. The goal is to uncover insights into passenger survival based on features such as sex, class, age, and fare.

📁 Files Included
Survival Count by Sex: A bar plot showing how survival varied between males and females.

Fare Boxplot: A boxplot highlighting the distribution and outliers in the fare data.

Survival Count by Pclass: A countplot showing the survival rate across different passenger classes.

Pairplot: A multi-variable scatterplot matrix to understand relationships between features like age, fare, and Pclass, colored by survival status.

Correlation Heatmap: A heatmap showing correlation coefficients between all numerical features.

📊 Visualizations Explained
Survival Count by Sex

Females had a much higher survival rate than males.

Visualized using sns.countplot() with hue set to Sex.

Fare Boxplot

Most passengers paid low fares.

A few outliers paid very high fares.

Created using sns.boxplot().

Survival Count by Pclass

Passengers in higher classes (1st class) had better chances of survival.

3rd class had the highest number of casualties.

Pairplot

Shows relationships among Age, Fare, and Pclass.

Orange points indicate survivors; blue indicate non-survivors.

Created using sns.pairplot().

Correlation Heatmap

Fare is negatively correlated with Pclass (higher class, higher fare).

Survival positively correlates with Fare and weakly with Parch and SibSp.

Created using sns.heatmap().

🛠️ Technologies Used
Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook (recommended)

📌 How to Run
Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Load the Titanic dataset into a pandas DataFrame:

python
Copy
Edit
import pandas as pd
df = pd.read_csv("titanic.csv")
Execute the code snippets in a Jupyter Notebook or Python script.

📈 Conclusion
The analysis provides clear evidence that gender and class significantly influenced survival chances. Higher fares and first-class passengers had better outcomes, and women were more likely to survive than men.

