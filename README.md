# FrontEndUI
UI Test Front end
I have implemented Automation Cucumber BDD,JUnit framework and Maven build management tool for UI front end test and used Java languages with Selenium automation tool.

Part 2(Front End test challenge test)
Cucumber framework is scenario based tool so we can write the test steps in Feature file. The advantages of this framework its easy to use,
maintanance and reusable.

Three important files
Feature (Creating the scenarios)
Step definitions(Java automation scripts)
Test Runner(to drive the execution)

Please find the below UI validations using automation scripts.
  Navigate to Free Now Url
	Validate Free Now Home page logo and title
	Validate Free Now Page headers 
	Validate total Taxi Count with total Table Count
	Validate Free Now clicking upon taxi details,status and conditions
	Validate Footer options Navigate to Next,Last,Previous and First page
  
I have executed the automation scripts in locally its executed successfully and deployed the scripts into Circleci server 
but due to server folder configuration error was thrown "Driver is not executable" though browser driver exe is placed in the project folder

Part 1(Front End test challenge test)
Test Strategy - Multi Mobility App

Taxi
    Accuracy of Data - We need to test data accuracy in multiple points this will include data of the customer,driver,trip details,offers and fares.
    Integrated Payment and Wallet - We need to test integrated payment gateway for every rides the payment should be done
    
    Customer Perspective
    	User and driver Registration
	Map and live tracking
	Time tracking
	OTP
	Payment transaction and history
	Trip modification
	Cab sharing
	Driver and cab details
	Search offers
	Feedback and rating system
	
     Driver Perspective
     	Driver data
	Trip visibility options
	Benefits and history
	Hiding customer data
	
Transport Tickets
	Filling the train/bus details From station,to station,departure date,list of available trains/bus are displayed
	Users can search for trains/bus by name,from to stations for checking the status
	Search results have details,timings and availability
	Clicking searching results and its routed to details of the page
	User is able to see availability of seats.
	User able to see train/bus fares for different types of seats
	User is able to select one or more seat
	If the Seats are booked already the user should not be able select the same seats
	User selects seats enters the passengers details then does the payment then selected seats should be booked
	Users can downlod/print the ticket
	User should receive the SMS for tickets confirmation
	If User cancel the ticket the amount should be refunded
	
	
