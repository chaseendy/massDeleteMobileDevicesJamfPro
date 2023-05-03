
# Mass Delete Mobile Devices in Jamf Pro
This script will take a list of mobile Device IDs exported from a Jamf Pro server and delete the devices from Jamf utilizing Bearer Token authentication and record the list in a predefined log file. 


#	USAGE: 
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

#	RUN COMMAND BELOW

		./mass_delete_Jamf_Pro_Mobile_Devices.sh jamf_pro_id_numbers.txt
		^^This will be the script name           ^^This will be the file of Jamf Pro Device IDs

