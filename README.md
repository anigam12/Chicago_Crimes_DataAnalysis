# Chicago_Crimes_DataAnalysis
Analysis of Chicago Crimes Record Data.

Chicago Crime Data
Data Source: chicagocrimes.csv

Part 1: Data Munging


Write a Nodejs program that converts the csv file into a json file that will be used to plot data in part 2. You have to come up with an optimal schema for the json file based on the requirements of Part 2.


Part 2: Data Visualization with D3.js


1. To make a stacked bar chart filtering on the following criteria and aggregated over the given time frame (2001 - 2016) :-

THEFT OVER $500

THEFT $500 AND UNDER


2. To make a multi series line chart of all Assault cases over the given time frame aggregated    on whether the crime resulted in an arrest or not.

## Getting Started

Download all the files to be able to successfully view the analysis results in the form of graphs.


### Prerequisites

```
-node js 

-http-server 
```
### Guide to files

The files you need to actually care about are-

1. chicago_crimes_csvtojson.js
2. index.html

Ensure that the other files are in the same directory as the above two.

3. chicago_crimes_graph1.json (stores the 'theft' data in JSON format for further use)
4. chicago_crimes_graph2.json (stores the 'assault' data in JSON format for further use)
5. d3.js , styles.css (required for styling the graphs)
6. theft.js, assault.js (required for plotting the bar graph and the multi line graph respectively)

### Installing

Step 1- Download the files to a local directory.

Step 2- Download the chicagocrimes.csv file from the web (http://172.23.238.252/csv_files)

Step 3- Run npm run lint (eslint validation) on the terminal from the directory.

Step 4- Run npm generate (This will create two JSON files (converted from csv format) : chicago_crimes_graph1.json & chicago_crimes_graph2.json (The two files have aggregated data as required in Part2(1 & 2))).

Step 5- Run npm start to start the http-server and view the graphs.

Step 6- Open the link on the browser to view the graphs for the data analysed.

```
Installation of http-server:

npm install http-server -g (This will install http-server globally so that it may be run from the command line)

```
Installation of eslint and validation

1. Go to the root directory
2. In the command Line type "npm init -y"
3. type "npm install eslint"
4. type "./node_modules/bin/eslint --init"
5. Follow the Steps (I have validated with airbnb)
6. type "./node_modules/bin/eslint chicago_crimes_csvtojson.js"

## Running the program

In the Command-Line TYPE(After cloning and putting csv in directory):

1. npm run lint (to validate the file with eslint)
2. npm run generate (to generate the JSON files)
3. npm start (to view the graphs)


## Built With

* []() - The web framework used
* [Node.js](https://nodejs.org/en/) - Dependency Management
* []() - Used to generate RSS Feeds



## Versioning

V1.0.0 

## Authors

* **Aradhika Nigam** - *Initial work* - [anigam12](https://github.com/anigam12)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

### Acknowledgments

* Mentors at StackRoute

