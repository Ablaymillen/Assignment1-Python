# Assignment1-Python
- Title: Filtering out top N cryptocurrencies by market capitalization using Pycoingecko and pandas
- Installation
In order to use this programm you must consider installing Pycoingecko and pandas libraries
- pip install pycoingecko
- pip install pandas
- Usage
To read data from api use read_API function
read_API(requested_json, number_of_rows)
- Usage examples:
read_API(requested_json= request, number_of_rows=10)
- This function will print out top 10 crypto currencies by their market capitalization place

- To store data in the CSV format for further observation and analysis use
- store_data(data_frame)
- Usage examples:
- Either store data retrieved from the read_API function to another variable or directly pass it to the store_data() funciton
- data_frame = read_API(report, 10)
- store_data(data_frame)
- Top 10 crypto currencies by their market capitalization place will be stored in the CSV format
