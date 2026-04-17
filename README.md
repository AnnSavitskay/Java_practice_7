# Java_practice_7
# Assignment for Practice #25 and #26

# 1) Obtaining data from an HTML page, creating and reading JSON files.
Obtains the HTML code of the "List of Moscow Metro Stations" page https://www.moscowmap.ru/metro.html#lines using the jsoup library.

Parses the resulting page and obtains from it:
- Moscow Metro lines (get line name, line number).
- Moscow Metro stations (get station name, line number).

Creates and writes to disk a JSON file with a list of stations by line and a list of lines in the following format:
![](https://github.com/artemmad/JavaAllExercices/blob/master/src/ru/mirea/exercies25and26/1.png?raw=true)

Reads the file and outputs the number of stations on each line to the console.
