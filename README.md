# EmployeeDetails
Read Before the execution:
1. H2 Database has been used for this project so that this project runs in every system irrespective of the availability of other databases
2. since H2 is an in house memory, hence it is auto deleted when the spring boot starts, hence the initial data load should happen manually.
3. Steps for manual loading of data:
	a. Open Data.sql in notepad / notepad++
	b. Run the spring boot application
	c. in any browser, log in to "http://localhost:8080/h2-console/"
	d. In the password field, please enter "root" [without double quotes] and click connect.
	e. Once you log in successfully, copy the insert statements from data.sql and paste it in the text area in h2-console.
	f. Click on run button.
	g. The data will be loaded.
