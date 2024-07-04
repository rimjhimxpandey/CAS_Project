Detailed Description: Main Project:
===================================
Navigate to Be. Cognizant Website and capture the user information.
Under People header Click on Rewards, life and work and click on Holiday Schedules.
Validate Tool Tip and Name of Holiday Schedules.
Get all the data present in Holiday schedules section.
Validate current year is displayed.
Select PDF from the filters and verify whether data is reflected based on filter.
Validate whether user can download all holiday calendars.
Click on Holiday calendar based on location.
Verify whether Holiday calendar name and Tool Tip are same.
Select three dots and click and Version history.
Get all the details of Version History


Key Automation Scope:
=====================
Handling alert, different browser windows, search option
Navigating back to home page
Extract multiple options items & store in collections.
Capture warning message
Data Driven approach.
Cross Browser Testing


Output: [Chrome and Edge]
=========================

Be.Cognizant Loaded
User info captured and printed
Navigated to Holiday Schedules
Name of holiday Schedules Validated
Current year Validated
PDF filter selected and verified
All files downloaded
Calendar selected based on location
Calendar name and tool tip validated
Navigated to version history
Version History details fetched


Frameworks used:
================
Project made in Maven by using JAVA 
Dependencies used in Pom.xml: (Selenium, WebDriver Manager, TestNG)
	
<dependencies>
  	
	<!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
	<dependency>
    	<groupId>org.seleniumhq.selenium</groupId>
    	<artifactId>selenium-java</artifactId>
    	<version>4.18.1</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/io.github.bonigarcia/webdrivermanager -->
	<dependency>
    	<groupId>io.github.bonigarcia</groupId>
    	<artifactId>webdrivermanager</artifactId>
    	<version>5.7.0</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/org.apache.poi/poi -->
	<dependency>
    	<groupId>org.apache.poi</groupId>
    	<artifactId>poi</artifactId>
    	<version>5.2.5</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/org.apache.poi/poi-ooxml -->
	<dependency>
    	<groupId>org.apache.poi</groupId>
    	<artifactId>poi-ooxml</artifactId>
    	<version>5.2.5</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/org.testng/testng -->
	<dependency>
    	<groupId>org.testng</groupId>
    	<artifactId>testng</artifactId>
    	<version>7.9.0</version>
    	<scope>test</scope>
	</dependency>
	
</dependencies>
