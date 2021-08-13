Project Wrokflow:

1- Page Object Model Framework “POM”:
BaseClass class contains both Setup and Teardown Functions with Annotations @BeforeMethod and @AfterMethod respectively to be executed before and after @Test
Class HomePage is used for identifying Web elements in Home Page webpage
Class LoginPage is used for identifying Web elements in Login Page webpage
Class RegisterPage is used for identifying Web elements in Register Page webpage

2- Test package
Contains RunTestCases it is the main Class that Extends from BaseClass to use Driver and other Methods to run our tests, and contains Test case methods with annotation @Test

In RunTestCases class objects are created from HomePage and LoginPage and RegisterPage classes to interact with their methods

Used Frameworks
1- TestNG
2- Page Object Model Design Pattern /Framework
3- DDT (Data-Driven Testing Framework)
