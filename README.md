# Student-Analysis-Performance
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv("student_data.csv")

print(df.head())
print(df.describe())

df["Math"].hist()
plt.title("Math Score Distribution")
plt.xlabel("Score")
plt.ylabel("Students")
plt.show()
