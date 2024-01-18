# Traffic Accident Statistics

This Python script reads data from a file named `traffic_accidents.txt`, processes the information, and generates tables displaying the total number of accidents and damage amounts by provinces and causes of accidents. The script includes the following features:

- Two-dimensional lists (`allProvincesAccidentCounts` and `allProvincesDamageAmountTotals`) to store the total number of accidents and damage amounts for each province and cause of accident.
- Function `get_accident_data_and_generate_lists` to read accident data from the file and update the lists accordingly.
- Function `display_table` to print tables showing the accident counts and damage amounts, including row and column totals.
- Proper handling of file-related errors using exception handling.

## Usage

1. Ensure you have a file named `traffic_accidents.txt` with the required data.
2. Run the script, and it will process the data and display tables showing the total number of accidents and damage amounts.

## Code Overview

The script is organized into several functions:

- `get_accident_data_and_generate_lists`: Reads accident data from the file and updates the two-dimensional lists.
- `display_table`: Prints tables displaying the accident counts and damage amounts, including row and column totals.
- `main`: Orchestrates the entire process, handles file-related errors, and calls the necessary functions.

## Sample Output

Running the script will generate output similar to:

```plaintext
Total Number of Accidents in a Year by Provinces and Causes of Accidents
Prov. Code   Overspeed        Rule Violation   ...   Total
----------   --------------- --------------- ...   -----
1            10              5               ...   30
2            15              8               ...   40
...
Total        200             100             ...   600

press any key and enter to continue...

Total Damage Amounts in a Year by Provinces and Causes of Accidents
Prov. Code   Overspeed        Rule Violation   ...   Total
----------   --------------- --------------- ...   -----
1            5000            2500            ...   15000
2            7500            4000            ...   20000
...
Total        100000          50000           ...   300000
