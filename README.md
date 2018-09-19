### Date created
2018-09-19

### Project Title
Explore regional bikeshare data

### Description
This python script asks the user for input directly in the terminal which filters data from the chosen city before calculating some statistics. After presenting statistics from the filtered data, the script then asks the user if they would like to see the raw data with 5 lines per page. Finally the script asks the user if they would like to restart their seach.

This project was submitted as coursework for Udacity's Programing for Data Science. 

### Files used
chicago.csv
new_york_city.csv
Washington.csv

### Requirements
This program is run in python and requires the latest version of Pandas. Before running this program please check your version of Pandas is 0.23.0 or higher. To install the correct version use the following command:

'pip install -r requirements.txt'

The program uses three files above. These files must be in the same directory as the bikeshare.py program.

### Usage
Using the program is fairly simple. Start the program in Terminal with

'python bikeshare.py'

The program will start by asking which city data you like to view. 

    - Enter the first letter or full city name and press enter. 

Next the program will ask you if you wish to view a specific month of data.

    - Enter the month to view or ther first three letters and press enter

    - Alternatively, you can enter all or just press enter to view all months

Finally the program will ask if you would like to sort the data by the day of the week.

    - Enter the day of the week or the first three letter

    - Alternatively, you can enter all or just press enter to view all days. 

The program will then present some statistics on the data you have chosen to filter. 

Finally, program will finish by offering you a choice to view the raw data from the DataFrame.

### Credits
Most of this progam was guided by the course template at Udacity: 
https://www.udacity.com/course/programming-for-data-science-nanodegree--nd104

I found inspiration for the divmod function here:
https://stackoverflow.com/questions/4048651/python-function-to-convert-seconds-into-minutes-hours-and-days

I found the to_string() method here: 
https://stackoverflow.com/questions/40278845/suppress-name-dtype-from-python-pandas-describe
