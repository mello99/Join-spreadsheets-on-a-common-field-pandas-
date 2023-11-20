import pandas as pd


# - Normalize whitespace
# - Remove special characters

#######################
### on id column:



df1 = pd.read_csv("CSV_1.csv")
df2 = pd.read_csv("CSV_2.csv")
df1["id"] = df1["id"]
df1["id"] = df1["id"].dropna()
df2["id"] = df2["id"].dropna()
df1["id"].dropna(inplace=True)
df2["id"].dropna(inplace=True)


concatenate = df1.merge(df2, how='outer', on="id")


print(df1.columns)
print(df2.columns)
print(len(df1))
print(len(df2))


concatenate.to_csv("Joined_CSV_1_CSV2_on_id_column.csv")
