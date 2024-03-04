In this project, we analyze the products' price from Amazon website and frequently update the price in a CSV dataset
# check_price() function:
- Connect to the url that we want
- Get the source code and specific information of the product like price, title by class, id property in HTML
- Create and append to update price into a csv file with the price updated once a day
# send_email() function:
- When the price is low, it will inform to your email to buy the product with a affordable price 
