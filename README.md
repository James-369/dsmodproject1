# dsmodproject1
Flatiron Data Science Bootcamp Module 3 Final Project " \n"
: Student Name : Pura Riggins 
: Student Pace : FullTime
: Schduled Project Review Date : 04/09/2020
: Instructor Name : Amber Yandow 
: Blog Post URL ":







			The importance of cleaning datasets
It is promotes good data minning practices and helps spot out information that is deemed as incomplete. Genres that have more than one value ( film ) can provide a much more acurate insight in regards to the modeling phase Regarding this issue I will use the drop comand due to the inaccurate estimations that will arise if used as it in result will be inefficient within an aggregate functions as the median, maxium values will be the same. Contrarily genres such as Action and Animation can be used to provide insight for other columns that are categorial in nature such as the (Studio_Brand or Year) for an overall estimatation such as the sum of the Brand's profits and overall Global_Gains for a spectic year. If the columns contains no null values then it is quite useful and will deliver some important insigh depeding on what specific manipulation technique is used. The quanitiy of specific unique objects such as Genre mite provide inaccurate details in regards to a quantitative estamation such as the sum if there only one, and may only be useful in an overall estiamation of the columns or useful for value_counts. It is up to the data scientist to decide whether if a columns can be of use The dimesions of the dataframe provides a scope of evaluating on which cleaning methods will be most apropiate to get rid of any dirty data. After evaluating the sum of duplicate rows within the dataframe equaling to 2 and varifying these findings through variables methods such as built-in functions like sum(), the uniqueness of films in comparison to the set's initial shape , and calling a for loop to interate and provide the full details on which in particular film is entered twice in general, I reached a conclusion on which one's to drop and each methods provides strong supporting evidence. The initial data types are also important factors that are influencial towards the data cleaning process and can be used as a guide for choosing the most appropiate methods. For Instance the column that includes a dollar sign in front of it's values are initally  defined as categorical and won't be of any valuable use until it is converted into an integer , float, or some format that is quantitative in nature for futher manipulation. Therefore a series of modifications must be completed on those columns in particular  for the purpose of certain specific built-in functions to properly calculate the values. What occurs if you don't convert the datatype of a column into it's most appropiate form for the specific manipulation technique? You will recieve an avalanche of errors with aftereffects of confusion, because data cleaning is a structured process that requires fudemental knowledge in order for the data scientist or analyst to be aware of what spefic changes will be needed to fulill the goal of manipulating that specifc datatype. Therefore it's crucial to ask questions concerning how can this be completed and what must be done first in order for it to be measured and assessed otherwise you will unable to properly conduct your analysis due to the lack of a structured formula , being a prequisite for science. 



