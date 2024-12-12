# FinalProjectScriptingLanguage

# Email Parser and Filter

## Purpose
This script provides a comprehensive email parsing and filtering utility that allows users to:
- Parse emails from a CSV file containing email metadata
- Filter emails based on multiple criteria
- Generate summary reports
- Export filtered results to new CSV files


## Installation
1. Ensure Python 3.8+ is installed

## Usage
python email_parser.py [OPTIONS]

Options:
    !!!!!!!!!   Please use -i for the best experience. I find it challenging to use the other options. The script is interactive and makes it much easier to go through the process of generating a report.



  -h, --help            Show this help message
  -f, --file FILE       Input CSV file with email data
  -s, --sender SENDER   Filter by sender (partial match)
  -b, --before DATE     Filter emails before this date (YYYY-MM-DD)
  -a, --after DATE      Filter emails after this date (YYYY-MM-DD)
  -o, --output FILE     Output filtered results to a new CSV
  -r, --report          Generate a summary report
```

Go through the steps by typing "python email_parser.py -i"