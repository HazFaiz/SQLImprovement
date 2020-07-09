# SQLImprovement

This is a list of written explanations for improving the given SQL query.

-Too much data is being selected, resulting in results that are hard to read. It would be more user friendly to separate the query into smaller selects that are relevant to each other (ie,name with id and job category, with a separate select for degrees and salary, etc) 

-It would be better to avoid multiple join statements

-the joins including IS NULL columns could be removed as no data would be returned.

-Could use wild cards in the LIKE statements to shorten the query

