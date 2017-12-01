# Seleniun Developer - SeDev

Selenium Developer assist Selenium developers in Design and Maintenance phase of automation development. It reduces time in doing for maintenance for application with frequent object changes.


**Features:**<br/>
1. **Page Object Extractor**<br/>
Page object extractor will extract objects/locators written in java file.As of now it supports<br/>
    a. Regular Java definition<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;Example : driver.findElement(By.locator("locatorKey"))<br/>
    b. POM (Page Object Model)<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;Example : By.locator("locatorKey")<br/>
    c. Page Factory model<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;Example : @FindBy(how = How.NAME, using = "q")<br/>
    d. enum pageobject definition<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;Example : lnk_LogInHeader("nav-bar-login-icon",ID,"Login Link"),<br/>

2. **Object Scanning**<br/>
Then extracted page object can be scanned over application UI to find its availability.<br/>

3. **Object locators**<br/>
Object Locator will suggest you with possible xpath that can be formed with element being located.<br/>

4. **Fiddle**<br/>
Fiddle is simple and small code editor designed to run selenium snippet. You can test your snippet of selenium code with fiddle without invoking browser everytime. Also you can run the selenium code on desired web page in the browser. Which will reduce your design effort, you don't need run whole testcase again and again to test a snippet of selenium code.<br/>
