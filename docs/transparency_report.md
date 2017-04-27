# Transparency Report

### Getting the Data
There are not many websites that have a data set containing all of the State of the Union Address and Addresses to a Joint Session of Congress. Additionally, the websites available are not conducive to webscraping because the html was not the same for each page. After several failed scrape attempts on three different websites we decided to follow a different approach: copy every address into individual .txt files labeled by the year it was given. We felt that The American Presidency Project had the most complete collection of addresses, and therefore used their data set.
[American Presidency Project: State of the Union Addresses and Messages](http://www.presidency.ucsb.edu/sou.php)
There were several years that multiple addresses were given (more on this later), so this is noted by a number after the year in the .txt file name.
![Text Files in Folder](imgs/txt_State_of_the_Union)
### Tools Used for Analysis
After the .txt files were gathered, they were loaded into the text analysis tool OverviewDocs for further analysis. OverviewDocs allows users to search each uploaded document for certain keywords and tag them for grouping purposes. We began tagging each document by the president who delivered the address, and then began searching various keywords such as "jobs", "Soviet Union", and "terrorism", tagging the documents containing such keywords.
![Overview Tags and Tree](imgs/overview_tree_and_tagging)
The tree search function progressively narrows down various keywords that are commonly found with one another in the documents and lists the documents where these keywords are found. Both of these processes were key to discovering meaningful relationships between the documents, which will be expanded on in the "Initial Findings" section.
