
# Henley Passport Index Dataset
The Henley Passport Index Dataset is a Python project that utilizes an API provided by the Henley Passport Index and converts the collected information into a structured CSV format that can be easily analyzed.

![Passport](world-flags.png)

## Description

This project extract the information from API provided by the Henley Passport Index, which is an interactive online tool that provides information about the visa requirements for different countries. It consumes API and converts it into a structured csv format that can be easily analyzed. The data is then saved as a CSV file that can be used for further analysis or visualizations.

## Dependencies
The project was developed using Python 3.8 and requires the following libraries:

- python 3.x
- pandas
- requests

## Output
The data will be saved in a CSV file named henley-passport-index-{date}.csv and henley-passport-index-count-{today_date}.csv in the same directory of project file. Previous historical data can be found inside folder named history. Two excel files are saved in the same directory.

- The first file consists of comprehensive information on visa requirements for different origin-destination pairs
- The second file consists of visa information for each country, including the number of countries offering visa-free access, and visa-required status.


## MIT License

This project is completely free of charge and has been constructed using information that is readily available to the public. The content featured on this platform has been generously contributed by devoted supporters as well as various governmental organizations from all corners of the globe. You are more than welcome to utilize the dataset available on Passport Index in accordance with the MIT license.

Source: https://henleyglobal.com/passport-index
