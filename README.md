Please import the external libraries in eclipse with these steps:
1. Right click Project
2. Click Built Path
3. Click Configure Build Path
4. Click Libraries
5. Click Add External JARS
6. Select all the files in Libraries folder
7. Click Open

Please download "Selenium GeckoDriver" from the path below and unzip the file:
1. https://github.com/mozilla/geckodriver/releases

Please update the path of webdriver.gecko.driver in my script and point it to the location of the gecko driver.
Example: System.setProperty("webdriver.gecko.driver", "C:\\Users\\cpoquiz\\Documents\\geckoFirefox\\geckodriver.exe");

"Selenium GeckoDriver" is used to open the firefox browser.

Please have the following: 
latest firefox browser, Java 8+, latest version of Eclipse

References: http://www.automationtestinghub.com/download-and-install-selenium/ 
http://www.automationtestinghub.com/selenium-3-0-launch-firefox-with-geckodriver/

The following assumptions are made since we are performing positive testing as per instruction:
1. All the test data (email address used) are not yet registered; 
2. No validation is done to check if the email address is registered already.
3. The email address provided are valid and are in correct format.
4. The validation on the "email address" textbox is working properly (required field, max number of characters, formats, allowed characters, delete value etc.).
5. The password provided are valid and are in correct format.
6. The validation on the "password" textbox is working properly (max number of characters, formats, allowed characters, delete value etc.).
7. Other links, buttons displayed in the page are properly working.
8. The UI is rendered properly.
9. The label texts, images, buttons, links, header title are aligned correctly.
10. All buttons are enabled.
11. The back and forward icons of the browser is out of scope.
12. The validation of the email link validity is out of scope.
13. Email Address is required.
14. Password is not required.
