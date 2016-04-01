# Skill Tracker

NOTE: This does not have any authentication for login.You need to design your authentication.

Before using the Web App read the following instructions

After doing $npm install and $npm start 

Assuming that the App is running on http://localhost:3000

1)
	If you want some test data in the database
	
	Open http://localhost:3000/create
	
	This will create the database of all required managers and employees , the details of the database are at the end
	Warning: After running it once dont run it again , as creating duplicate users will throw an error
    
2)
	In case if you want to delete everything from the database and start using the fresh app
	
	Open http://localhost:3000/delete
	
	Warning: This will delete all the users , certificates , clients and logs    
	
3) 
	To check the database of managers and employees in raw format 
	
	Open http://localhost:3000/check
    
4) 
	To check the database of available skills in raw format 
	
	Open http://localhost:3000/skills    
	
5) 
	To check the database of available certificates in raw format 
	
	Open http://localhost:3000/certificates
    
6) 
	To check the database of available clients in raw format 
	
	Open http://localhost:3000/clients    
    
7) 
	To check the logs of the activities 
	
	Open http://localhost:3000/logs	
	

	
	
--Database for testing--

[I] manager1 is connected to employee1 and employee2

[II] manager2 is connected to employee3 and employee4
_____________________________________________
|        Username          |    Password    |
|--------------------------|----------------|
|   manager1@email.com     | 	manager1    |
|   manager2@email.com     |	manager2    |
|   employee1@email.com    |	employee1   |
|   employee2@email.com    |	employee2   |
|   employee3@email.com    |	employee3   |
|   employee4@email.com    |	employee4   |			 	
|__________________________|________________|

Available Skills:

	Developer - Coding - Java
	
	Developer - Coding - C#
	
	Developer - Testing - Manual
	
	Developer - Testing - Selinium
	
	Management - Resource - Employee Manage
	
	Management - Resource - Project Handling
	
	Management - Customer Handling - Client Success
	
	Management - Customer Handling - Client Relationship

Available Certifications:  Java , SI , Oracle , C , C++ , JavaScript , MySQL , MongoDB

Available Clients:  Nike , Adidas , ITC , Titan , Puma , Red Bull
	
	(These are only for testing purpose and not for advertisement)		


