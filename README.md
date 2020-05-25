Instructions - angel source 3
========
  1. Fork this repository:  https://github.com/bentoihelloworld/techxplore.git
  2. Clone the forked repository to your local system.
  3. Complete and fix the code for the following:
		- frontend (grocerybill-ui)
		- backend  (grocerybill-ws)
  4. Push your answers to your GitHub repository (techxplore).
  5. Open a pull request 
  6. Add comment with your complete name and email and send.
  
 Requirements for you to complete the code
 =======
 
 grocerybill-ws
  -------
 1. Should be able to get data from the repository.
 2. Should be able to expose these endpoints.
	- /items/bill/regular
	- /items/bill/discounted
 
 
 grocerybill-ui
 -------
 1. Should consume regular and discounted bill from the grocerybill-ws 
 2. Should be able to add the attribute from regular and discounted bill using model interface so that view can easily access the data.
 3. Should enable client side load balancing using ribbon
 4. Should access using this URL: http://localhost:7070/techxplore/grocery

	
HAPPY CODING :D