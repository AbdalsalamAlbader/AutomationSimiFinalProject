📘 AutomationSimiFinalProject
This is an automated testing project using Selenium WebDriver, TestNG, and Java, designed to perform a series of tests on the practice site https://codenboxautomationlab.com/practice/.

📁 Project Structure

AutomationSimiFinalProject/
└── src/
    └── AutomationSimiFinalProject/
        └── AppTest.java
🔧 Prerequisites
Before running this project, ensure you have the following installed:

Java JDK 8 or later

Maven or Gradle (optional, if using build tools)

TestNG

Chrome Browser

ChromeDriver (Ensure it matches your Chrome version and is in system PATH)

📦 Dependencies
Add the following to your pom.xml (for Maven):


<dependencies>
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.17.0</version>
    </dependency>
    <dependency>
        <groupId>org.testng</groupId>
        <artifactId>testng</artifactId>
        <version>7.10.0</version>
        <scope>test</scope>
    </dependency>
</dependencies>
🚀 How to Run
Clone the repository or open the project in your IDE (like IntelliJ or Eclipse).

Make sure ChromeDriver is installed and accessible via PATH.

Enable the desired test by setting enabled = true in the corresponding @Test annotation in AppTest.java.

Run the test as a TestNG test.

✅ Test Cases Included
Test Method	Description
RadioButton	Selects a random radio button.
autoCompleteTest	Tests autocomplete country input.
selectTag	Selects an option from a dropdown.
CheckBoxTest	Randomly selects checkboxes.
window__Example	Switches between browser windows.
Switch_Tab_Example	Switches between browser tabs.
AlertTest	Handles browser alert and confirm dialogs.
TableTest	Extracts and prints table data.
HideAndShow	Tests hide/show functionality of an input field.
EnableAndDisable	Tests enabling/disabling of an input field.
MouseHover	Performs mouse hover actions and reloads page.
calender	Navigates booking calendar and extracts dates.
Iframe	Handles iframe switching and nested window operations.
Download	Clicks a button to initiate APK file download.

📌 Notes
You can randomize or specify the selections as needed using comments in the code.

Adjust wait times if you encounter synchronization issues.

🧑‍💻 Author
Abdalsalam
Project created for practice and demonstration of Selenium + TestNG skills.