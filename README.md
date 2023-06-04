# Task-2
import pandas as pa

# Load the dataset into a DataFrame

data = pd.read_csv('kaggle datasets download -d gokulrajkmv
/unemployment-in-india')

 # Display the first few rows of the dataset
 print(data.head())

# Perform data analysis or visualization casks
 # Example: Calculate the average unemployment rate
 average_unemployment_rate = data('Estimated Unemployment Rate
. mean()
 princ("Average Unemployment Rate:", average_unemployment_rate)

 # Plot the employment rate over time import matplotlib.pyplot as plt

data['Date'] = pd. co_datetime (data ['Date'])
 plt.plot(data ['Dare'], data['Estimated Employed' ])
 plt.xlabel ('Date')
plt.ylabel( 'Employment Rate' )
 pLE. title(' Employment Rate Over Tine') I
 plt. show()
