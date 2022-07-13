# District-Wide Analysis of Standardized Test Data (using Python & Pandas)

## Project Overview
Our client is Maria, a public school official, who is responsible for analyzing, reporting, and presenting district-side analysis of standardized test scores in Math & Reading to provide insights into student performance & proficiency patterns and trends. She wishes to analyze data from different schools, individual students (within schools), and learning domains (reading, math). Results will be presented to the school board, which will use this information to inform budget allotments (funding priorities). Maria has requested the following deliverables:  
	<ol>
	<li> A high-level snapshot of the district's key metrics, presented in a table format
	<li> An overview of the key metrics for each school, presented in a table format
	<li> Tables presenting each of the following metrics:
	<li> Top 5 and bottom 5 performing schools, based on the overall passing rate
	<li> The average math score received by students in each grade level at each school
	<li> The average reading score received by students in each grade level at each school
	<li> School performance based on the budget per student
	<li> School performance based on the school size 
	<li> School performance based on the type of school
	</ol>

## Resources (Source Data & Analysis Software)
To accomplish these tasks, we used the following resources:
	<ol>
	<li> Data Source = (1) 'schools_complete.csv' and (2)'students_complete.csv'; and
	<li> Software = Python (v 3.9.7); Jupyter Notebook;
	</ol>

The first source data file (filename = 'schools_complete.csv') has the following structure:
	<ol>
	<li> It 16 rows (first row contains headers);
	<li> It contains 5 columns:
		<ol>
		<li> Column A contains Indices (0-14)
		<li> Columns B-C contain string data (school names & types)
		<li> Columns D-E contain numeric (integer) data 
		</ol>
	<li> The headers (Keys) are:
		<ol>
		<li> "School ID"
		<li> "school_name"
		<li> "type" {District, Charter}
 		<li> "size" (number of students)
		<li> "budget"
		</ol>
	</ol>
At a glance, there do not appear to be any anomalies in this data set (e.g., no missing data or mis-matched data types).

The second source data file (filename = 'students_complete.csv') has the following structure:
	<ol>
	<li> It 39171 rows (1st row contains headers);
	<li> It contains 7 columns:
		<ol>
		<li> Column A contains Indices (0-39169, n=39170 rows of data)
		<li> Columns B-E contain string data (student names, grades, & school)
		<li> Columns F-G contain numeric (integer) data 
		</ol>
	<li> The headers (Keys) are:
		<ol>
		<li> "Student ID"
		<li> "student_name"
		<li> "gender" {M, F}
 		<li> "grade" {9th, 10th, 11th, 12th}
		<li> "school_name"
		<li> "reading_score"
		<li> "math_score"
		</ol>
	</ol>
Pivot table summary shows that data are relatively clean. There are minor issues with consistency (e.g., some student names are preceded or followed by titles, such as "Dr." or "MD"). 

## Python Analysis
We used python methods -- .count(), .notnull(), & .isnull() -- to confirm that there are missing values in the data.

We then used Python (v 3.9.7) to automate the analysis and to output analysis results to a text (.csv) file, as described below.

## Results (Files Created)
The XXX code that we created resulted in the following outputs (files created):
	<ol>
	<li> Data Analysis Results File = 'XXX'; and
	<li> XXX Script = 'XXX';
	</ol>

The analysis results file (filename = 'XXX') has the following structure:
	<ol>
	<li> It contains XXX rows (including a title row and XXX rows with tabulated results);
	<li> The first row of tabulated results shows XXX;
	<li> The next XXX rows show XXX; and
	<li> The final XXX rows show XXX.
	</ol>

The XXX script (filename = 'XXX') has the following structure:
	<ol>
	<li> It contains XXX rows (including rows with code comments and annotations);
	<li> The first chunk of code imports dependencies (python modules);
	<li> The next chunk of code declares and initializes key variables (including empty lists and dictionary objects);
	<li> The subsequent chunk of code opens and reads the source (.csv) data using python; 
	<li> The next several chunks of code determine XXX; and
	<li> The final chunk of code prints results to the terminal and saves them to a text file.
	</ol>

## Summary & Conclusions
Analysis results suggest the following conclusions:
	<ol>
	<li> XXX.
	<li> XXX:
		<ol>
    		<li> XXX,
        	<li> XXX, and
        	<li> XXX.
		</ol>
	<li> XXX:
		<ol>
    		<li> XXX;
        	<li> XXX; and
        	<li> XXX;
		</ol>
	<li> XXX.
	</ol>


