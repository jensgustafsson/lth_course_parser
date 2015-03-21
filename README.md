# lth_course_parser
A parser to parse data about the courses at LTH written in ruby. 
The following gems are needed to run the script: 

* nokogiri 
* open-uri

To run the script you type the following: 

ruby course_parser.rb PROGRAM YEAR LANGUAGE,

* PROGRAM is the letter of the queried program(example 'D' for datateknik or 'M' for maskinteknik
* YEAR has the syntax XX_YY (example 14_15) where XX is the start of the study year and YY the end of the study year
* LANGUAGE are either 'en or 'sv'
