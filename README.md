After reading about the Piotroski Valuation, I thought that it might be interesting to code it in Python utilizing professional grade data from Quandl to see what the results could be.  

# Dataset 
Sharadar is the data provider for this project and the link below shows what type of data they provide.
https://www.quantrocket.com/docs/data/fundamental/sharadar/

# Notes
This code isnt cleaned up to perfection as there are still some pieces of commented out code that didnt work or weren't as efficient as I wanted, but it runs efficiently via Google's Datalab, only utilizing their 3.5gz Virtual machine.

# Requirements
- Python 3.6
- Pandas
- Quandl

# Extra
- This code should be cleaned up soon as there are things that can be modified or it being automated more efficiently.
- The reason why there is still a pip install in the code is that Google's datalab does not remember packages that I would state as "out of the norm" such as Quandl which is why it is left in the code.
- You will have to sign up for the dataset via Quandl as my API key isnt 'key'
