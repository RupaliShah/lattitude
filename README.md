# What's the weather like...

Weather of randomly selected 500 unique cities based on latitude and longitude is visualized utilizing Python libraries [citipy Python library](https://pypi.python.org/pypi/citipy), Matlpotlib, and Seaborn, and the [OpenWeatherMap API](https://openweathermap.org/api). Weather check of each of the cities is performed using a series of successive API calls. The retrieved data is saved as a .csv file. The visualizations are displayed on the [web](https://rupalishah.github.io/lattitude/).

The website consists of 7 pages total, including:

* A landing page 
* Four visualization pages
* A Comparisons page that uses a bootstrap grid for the visualizations.
* A Data page that displays a responsive table containing the data used in the visualizations.The data is converted from .csv to html using a csv-to-html table conversion tool [ConvertCSV](http://www.convertcsv.com/csv-to-html.htm).
* The [website](https://rupalishah.github.io/lattitude/) is deployed using github pages.
