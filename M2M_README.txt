Contact: Leonardo Lopez | leonardo.rath@gmail.com


*modified files
	inst/app/global.r

*default data location
	inst/app/data

HOW TO CHANGE DEFAULT DATA

1. Place the dataframes to display as default on the data folder

2. On the global.r file add the following line of code at the bottom of the file:

	options(radiant.init.data = list.files(path = "data/", full.names = TRUE))

