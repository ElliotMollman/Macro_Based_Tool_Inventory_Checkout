#Tool Sign-Out Sheet



#Operations:

#Sign-Out Operation - Once the operator enters the tool number, their initials, the dash number if possible, and their workstation number, the program searches the entire workbook except for the “Sign-Out-Log” and “Tool_Checkout” sheet, and copies them to the “Tools Currently In Use” table. 

#Sign-In Operation - After the operator enters the tool number, the dash number if possible, and their initials, the program searches the table for those values and copies them to the “Sign_Out_Log” before removing them.

#Clear Log File - This operation automatically clears the log sheet.

#Additions:

Input values follow strict formats, preventing operators from entering incomplete or incorrect values. 

Example for tool:		 Letters-Letters-Numbers.   		TEI-C-100.
		   
Example for Initial:		 2 Letters   		    		EM.
		  
Example for dash number:	-Numbers				-12
		   
Example for workstation: 	2 Letters - Numbers			WS-23



Messages will be displayed when the format doesn’t match, and will identify which input was incorrect.

Number of Log entries are tracked, with a maximum of 100.

Added tracker for amount of tools due for calibration.
