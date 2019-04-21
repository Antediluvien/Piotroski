# Objective
After reading Jospeh D. Piotroski's paper on Value Investing: The Use of Historical Financial Statement Information to Separate Winners from Losers, I wanted to see how many companies pass this very specific set of parameters for fundamental analysis.

# Approach
I developed an alogorithm utilizing Python 3.6, a virtual machine from Google's Datalab as my environment, and the Python library Pandas for dataframe manipulations.

# Dataset 
Sharadar is the data provider for this project and the link below shows what type of data they provide.
https://www.quantrocket.com/docs/data/fundamental/sharadar/

# Notes
This code isnt cleaned up to perfection as there are still some pieces of commented out code that didnt work or weren't as efficient as I wanted, but it runs efficiently via Google's Datalab, only utilizing their 3.5gz Virtual machine.
- The reason why there is still a pip install in the code is that Google's datalab does not remember packages that I would state as "out of the norm" such as Quandl which is why it is left in the code.
- You will have to sign up for the dataset via Quandl as my API key isnt 'key'

# Requirements
- Python 3.6
- Pandas
- Quandl
