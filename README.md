# WebAutomation

This project contains the following four test cases in the following website:
WebSite Name: Books application:: https://demoqa.com/books

1. Navigate to the URL. Search for the keyword 'JavaScript' and select the Book 'Programming JavaScript Applications' by Author Eric Elliott.
Assertions: On selecting the mentioned book the application should navigate to the book details page. Also, validate the Book name & Author with the above given details against the UI.
2. Click in Forms in the left panel and choose Practise form. Fill out the student form using data from an Excel sheet.(Precondition: Create a Excel sheet with 5 Student records with fields as required in UI). Run the test for 5 times, so 5 student records are created.
3. Click on Elements-> Web Tables from the left panel. Read the web table data from UI web table to a new worksheet in the already existing excel workbook as stated in Use case no.2.
4. Click on Interactions->Sortable from the left panel. The numbers would be sorted in Numerical ascending order from 'One, Two, Three, Four, Five, Six'. You have to drag n drop the values to sort in numerical descending order as in 'Six, Five, Four, Three, Two, One'.

This project has following Components:
Selenium with Java
Page Object model design pattern
TestNG
ExtentReport
