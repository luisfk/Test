# Test
import pandas as pd
df = pd.read_csv("Data_AAPL_2020_06_02.csv", delimiter=";")
df.loc[df["Symbol"] == "AAPL"]
print(df.Symbol)

