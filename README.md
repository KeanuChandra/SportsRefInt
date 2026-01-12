My solution is relatively simple but offers a good level of efficiency. I convert the JSON data into a dataframe using Pandas. I can now easily manipulate the data using the Pandas dataframe. 
I iterate through each cell (which is now a dictionary with 2 keys, 'W' and 'L') in the dataframe and replace the dictionary with just he value of ['W']. This takes O(n) time where n is the number of cells. I then convert to Int64 to remove the trailing .0. 
I then reorder the columns as specified in the prompt and print the dataframe to show a table that looks similar to what was asked for. 

My code can be fully run as a Jupyter notebook with the sample JSON I have provided to get the exact ouput.
