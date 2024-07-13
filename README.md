# BBIM502_A2_Project_764708057_1
# Introduction on how to operate the given Python code in jupyter notebook
# This is a Hotel management system function. 
This hotel management system is developed to handle room allocation, billing, and the record management of the hotel rooms. The system is implemented using Python language. It provides functionalities to add, delete, and display rooms, allocate rooms, de-allocate rooms, and billing, save the allocations to files,and create a backup file for the allocation data. 
# Features
* Add room: Add a new room with basic details such as room ID, room type, and price. 
* Delete room: Delete room using room ID
* Display room details: Displays the details of the rooms in the system
* Allocate room: Allocate an available room to a customer using their name and check-in date.
* Display room allocation details: Displays the details of all the room allocations.
* Billing and de-allocation: Calculates the bill for the stay by calculating the period of stay using the check-out date and check-in date. displays the billing details and de-allocates the room.
* Save room allocations to file: Save all the current room allocations to a new file and name it 'LHMS_Studentid.txt'. 
* Show room allocations from file: Displays all the room allocation details save in the file 'LHMS_Studentid.txt'.
* Backup room Allocations file: Back up the room allocations file with a timestamp and clear the original file. 
# How to operate the code. 
* First you have to download Anaconda Navigator and open Jupyter Notebook. After signing in you have to go to the file option in the toolbar and select 'New', and then you have to select the 'Notebook' option there. After this, you have to select the kernel as Python 3 (ipykernel). After doing all these steps you will have a new Notebook ready for executing the given Python code.
* In the new notebook you have to copy and paste the code shared in the GitHub repository. Then you can run the main script using shift+enter.
* Follow the on-screen menu to perform various operations:
  1. Add Room
  2. Delete Room
  3. Display Room Details
  4. Allocate Room
  5. Display Room Allocation Details
  6. Billing and De-allocation
  7. Save Room Allocations to File
  8. Show Room Allocations from File
  9. Backup Room Allocations File
  0. Exit Application
* After you run the code you will see the menu on your screen and you can input the option you wish to execute using the numbers given to the options.
* If you select 1 as the option you will be able to add new rooms to the system using room ID, room type, and price.
* If you choose 2 you can delete a room you don't want anymore from the system by adding the room ID
* If you choose 3, you will be able to see the details of all the rooms in the system.
* If you choose 4, you can allocate a customer to a room using room ID, customer name, and check-in date.
* If you choose 5, you will be able to see the details of all the allocations.
* If you choose 6, and input the room ID to de-allocate, and the check-out date you will be able to generate the bill for the stay. You can get the billing details on the screen and then the room will be successfully de-allocated.
* If you choose 7, then a new file named 'LHMS_Studentid.txt' will be automatically created and all the allocation details will be saved in that file automatically.
* If you choose 8, the saved allocation details from 'LHMS_Studentid.txt' will be displayed as the output.
* If you choose 9, the 'LHMS_Studentid.txt' file will be backed up in a new file named 'LHMS_Studentid_Backup_Date_Time.txt'.
* And finally,  if you choose 0 the application will be exited.
# Error & exception handling.
This application includes many error handling in various scenarios. The purpose of this is to run the application smoothly. Specific exceptions will be caught and appropriate error messages will be displayed to the user. 
