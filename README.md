# ProgrammingAssignment2
Reads string up to 1000 chars and converts numbers within string to hex

Algorithm:
1) Request input
2) Read input
3) Store input
4) Find beginning and end of first number in string
	If invalid --> print NaN --> move to next number
	Else --> call subprogram 1 to convert chars to hex
		--> call subprogram 2 to convert entire word
		    (use reg to pass param; use stack to return value)
			--> call subprogram 3 to print
			    (use stack to pass param to subprogram 3)
