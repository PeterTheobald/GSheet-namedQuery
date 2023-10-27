# GSheet-namedQuery
provides a way to use the query() function with column names instead of column letters

GSheet-namedQuery - 2023 @ControlAltPete
Usage: in a Gsheet cell: =query( range, namedQuery( range, "SELECT [name], [age] WHERE [age] >=18"))
Converts the column names to Coln references by examining the headers in the range
Protects the query so it still works if you insert/delete new columns

See example sheet at: https://docs.google.com/spreadsheets/d/1N8sJfrf7arDzGu2nLr50ZyVCq6WamjKLANVU6kwx83k/edit#gid=0


