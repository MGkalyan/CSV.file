
import pandas as pd
data = {
    'Name': ['John', 'Alice', 'Bob'],
    'Age': [25, 30, 22],
    'City': ['New York', 'San Francisco', 'Chicago']
}


df = pd.DataFrame(data)

# Specify the file name
file_name = 'example.csv'

df.to_csv(file_name, index=False)

print(f'CSV file "{file_name}" has been created using pandas.')