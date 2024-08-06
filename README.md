# python-api-challenge

My code for this challenge can be found in the folder titled `WeatherPy`. The code I wrote is in the files called `WeatherPyWorking` and `VacationPyWorking`. The starter code files, which I used as the basis of my code, are in their own folder called `starter_code`, and are titled `WeatherPy` and `VacationPy` respectively.

The `.csv` files and `.png` files which are created when the code is ran are put into their own folder titled `output_data`.

There are a few places where I strayed a bit from the starter code. First, I reduced the sample size a bit in `WeatherPy` from 1500 random coordinates to 1000. This was because I wanted to reduce the risk of making too many API calls and being charged for it; also, it was taking a very long time to run that many requests. I still had a sample size of 441 cities, which seemed to be sufficient in drawing some correlations and doing some analysis.

I also formatted my regression charts a bit differently than how they are formatted in the sample solution. Instead of printing the regression equation on the chart itself using the `plt.annotate()` function, I printed it directly above the chart using the `print` statement. As I defined a linear regression function at the top of the code, I was having an issue in which the annotation was appearing on the chart always in the same place: good for some charts, bad for others. Printing the equation as text above the chart resolved this issue, and I feel also results in a cleaner-looking, less distracting visualization.