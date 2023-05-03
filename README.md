
# Mass Delete Mobile Devices in Jamf Pro
This will take a list of mobile Device IDs exported from a Jamf Pro server and utilize Bearer Token authentication to delete the list of devices and record the list in a log file. 


#	Usage: 
		Place in the same directory
			- .txt file labeled ---> jamf_pro_id_numbers.txt
			- .sh file labeled ----> mass_delete_Jamf_Pro_Mobile_Devices.sh

		Call script with the following four parameters
			- a text file containing the Jamf Pro IDs of the mobile device(s) you wish to delete.
			- The URL of the appropriate Jamf Pro server
			- username for an account on the Jamf Pro server with sufficient privileges
			  to delete mobile devices from the Jamf Pro server.
			- password for the account on the Jamf Pro server

#	EXAMPLE OF USE: 
		Change Directory on Terminal to the folder with the script and txt file

#		RUN COMMAND BELOW

		./mass_delete_Jamf_Pro_Mobile_Devices.sh jamf_pro_id_numbers.txt

