Mule 4 error handling framework directly handles the exception
errorhandling types
	1. mule default
	2. application level
	3. global error handling
	4. flow level
	
error handling mechanisms
	1. error continue - On-Error Continue catches the error and does not report it as an error
	2. error propagate -  On-Error Propagate processes the error message and re-throws the error to its parent flow
	3. try catch scope - we can put our component in the try block.