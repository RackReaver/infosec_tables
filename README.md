# InfoSec Tables

This repositiory is for storing tables to be using in SEIM tools (specifically Sumologic). The example documentation and help text will be for Sumologic, data can still be copied and moved around to allow for use in any SIEM for infosec tool.

## Getting Started

Access to a Sumologic instance is required to use the following instrucutions. That data can still be sourced for other SEIM or InfoSec tools but no instruction will be provided.

### Structuring .csv files for use in Sumologic
* The CSV file must contain a header line.
* The header line cannot use special characters.
* All values in the CSV file need to be wrapped in quotes.
* No spaces are allowed between quotes and values. For example:

Please see the Sumologic documentation to verify requirements have not changed: [Structuring .csv files for use in Sumologic](https://help.sumologic.com/05Search/Search-Query-Language/Search-Operators/lookup#structuring-csv-files)

## How to use
```
lookup <data_field>, <date_field>... from <raw_github_csv_link> on <src_lookup_value>=<dest_lookup_val>  
```
| Variable            | Description                                        |
|---------------------|----------------------------------------------------|
| data_field          | Comma seperated list of data to be imported        |
| raw_github_csv_link | Link to the raw Github page for Sumologic to parse |
| src_lookup_value    | Value in Sumologic to search against               |
| dest_lookup_value   | Value to match against in the Github csv page      |

## TO-DO
* Task 1
* Task 2
* Task 3

## Authors

* **Matt Ferreira** - *Developer* - [RackReaver](https://github.com/RackReaver)

## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details