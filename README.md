# QA_Website_Test_HW_20180512

# Used softwares

	Visual Studio 2017 Community
	Google Chrome (latest)
	Firefox ESR
	Selenium IDE 2.9.1	
	
# DoclerStudyTCs project

	Contains:
		- UnitTest1.cs which contains the TestMethod and calls the methods from the TestClass.cs
		- TestClass.cs which calls the page objects
		- 3 page objects (covers all pages)

	Packages:
			- MSTest.TestAdapter.1.2.0
			- MSTest.TestFramework.1.2.0
			- NUnit.3.10.1
			- Selenium.Chrome.WebDriver.2.38
			- Selenium.Support.3.12.0
			- Selenium.WeDriver.3.12.0
			
			
	This project is a unit test project (in C#) which contains the automated test.
	The aim of this project is to test automatically all the 12 requirements. 
	The page objects contain the commands. The HomePage.cs not just contains the
	commands for the 'Home Page' but for the 'UI Testing' page as well. Also there are
	some test requirements which concern to the 'Form Page' too, and it was simplier to
	test those withni this .cs file. For other information please see the comments in
	the code. In Visual Studio use Test Explorer to run the tests.
	

# GherkinTCs project

	Contains:
		- DoclerWebsiteTestScenarios.feature (+ DoclerWebsiteTestScenarios.cs)
		- DoclerWebsiteTestScenariosSteps.cs

	Packages:
			- SpecFlow.2.3.2
			- SpecFLow.NUnit.2.3.2
			- NUnit.3.0.0
			- Selenium.Chrome.WebDriver.2.38
			- Selenium.Support.3.12.0
			- Selenium.WeDriver.3.12.0
			- Newtonsoft.Json.9.0.1
			- System.ValueTuple.4.3.0
			
	This project is a standard console application with a SpecFlow feature file. In this project
	we are using the gherkin language. The aim of this project is to write test cases to reach 
	100% requirement coverage. The .feature file contains the 5 scenarios which cover the 12 test
	requirements. The Steps.cs contains the step definitions using NUnit and Selenium commands.
	For more information please check the .feature description. In Visual Studio use Test Explorer 
	to run the tests.
