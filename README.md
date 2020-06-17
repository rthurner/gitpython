# gitpython

# convert a downloaded watchlist of yahoo-finance.cvs
# the cvs content
- the watchlist contains an entry for each transaction made
and also an entry for shares without transactionns
-  it can be created with yahoo-finance and downloaded as cvs
# purpose of conversion
- drop entries without transactions
- drop some columns
- consolidate transactions
- calculate totals for each relevant column
# solution
- read csv-file into dataframe
- process the dataframe
- store the dataframe as csv
- store as to_excel 

