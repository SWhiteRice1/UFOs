# UFOs
## Project Overview
The purpose of this project was to create a webpage to filter data on UFOs. Data must be filtered by date of sighting, city, state, country, and shape of UFO.

## Resources
- Data Source: data.js
- Software: Visual Studio Code 1.38.1

## Results
To perform a search of the data, you can use the the five filters.

 ## Challenge Summary
 As the election commission reviews the results of this election and this script, the value of this script should be seen clearly. By utilizing this code, it will allow you to quickly analyze election results by county and candidate to determine the winner and where majority of the voters are from to determine the accuracy and reliability of the vote. To reuse the script, ensure the csv file path and txt files that are created are correct.
- The file path and txt.file can be corrected beginning in line 5 of the code as seen below:
```
# Add a variable to load a file from a path.
file_to_load = os.path.join("Resources", "election_results.csv")
# Add a variable to save the file to a path.
file_to_save = os.path.join("Resources", "election_analysis.txt")
```
Overall, this script is easilsy replicated and analyzed with simple updates to where to glean the data from for other congressional, senatorial, or even Presidental elections. However, presidential elections may also require to review by state which would require additional information on State in the election_results file.
