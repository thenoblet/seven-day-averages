# seven-day-averages
I used [New York Times repository](https://github.com/nytimes/covid-19-data) of live, cumulative COVID data to calculate new daily cases, create a 7-day average, and compare this week’s average to the previous week.

The code for this problem uses the Python requests library to access the New York Times data stored in an accessible GitHub repository. This is stored as a CSV file. The program then uses DictReader to read the CSV file. It then creates a States list to use selected States for calculations.

USAGE:
- $ python seven-day-average.py
- Choose one or more states to view average COVID cases.

- State: Massachusetts
- State: New York
- State:

OUTPUT example:
- Seven-Day Averages
- Massachusetts had a 7-day average of 1646 and an increase of 46%.
- New York had a 7-day average of 7502 and a decrease of 1%.
