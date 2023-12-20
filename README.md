# CSV.file
import pandas as pd

# Data to be written to the CSV file
data = {
    'Name': ['John', 'Alice', 'Bob'],
    'Age': [25, 30, 22],
    'City': ['New York', 'San Francisco', 'Chicago']
}

# Create a DataFrame
df = pd.DataFrame(data)

# Specify the file name
file_name = 'example.csv'

# Save the DataFrame to a CSV file
df.to_csv(file_name, index=False)

print(f'CSV file "{file_name}" has been created using pandas.')