# Selenium_Project
building a project using selenium and java using chrome driver<br>
<br>
**SELENIUM** : A powerful framework  for  testing web  applications.<br>
<br>
**History** <br>
&emsp;      2004 : selenium 1.0 <br>
&emsp;      2006 : selenium webdriver<br>
&emsp;      2009 : selenium webdriver 2.0<br>
&emsp;      2016 : selenium webdriver 3.0<br>
      <br>
Currently licensed under Apache 2.0 license<br>
<br>
Selenium project offers :<br>
 &emsp;                       WebDriver API : allows developers to write tests that automate a browser from a seperate controlling process.<br>
 &emsp;                       Browser Drivers<br>
 &emsp;                       W3C specification<br>
<br>
Other projects are like **Selenium Grid** which provides a central hub that allows multiple selenium tests to run concurrently with a lot more configurations,<br>
and other one is **Selenium IDE** which is a firefox plugin used to record each interaction of an application as tests steps<br>

**Selenium Webdriver**
<br>
Using a webdriver provides <br>
&emsp;        <b>Quickly and easily write automated tests<br>
&emsp;        maintain a standardized API that is user friendly<br>
&emsp;        Emulate actions of users<br></b>
<br>
**SELENIUM ARCHITECTURE**

    **TEST SCRIPTS** <-----> **WebDriver API** <-----> **Browser**

**BROWSER DRIVER**

&emsp;  ChromeDriver is for Chrome<br>
&emsp;  geckodriver is for Firefox <br>
&emsp;  Edgedriver is for Microsooft edge <br>
&emsp;  safariDriver if for aple browser <br>
&emsp;

<br>

**Now Let's set up a Meaven Project for Selenium test cases**
<br>
1. Add the **selenium dependencies** in pom.xml file of project so that we can import the required modules and libraries while writing test cases.
   
   <dependencies>
        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-java</artifactId>
            <version>4.18.1</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-api -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-api</artifactId>
            <version>4.18.1</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-chrome-driver -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-chrome-driver</artifactId>
            <version>4.18.1</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-server -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-server</artifactId>
            <version>4.0.0-alpha-2</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-support -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-support</artifactId>
            <version>4.18.1</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-remote-driver -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-remote-driver</artifactId>
            <version>4.18.1</version>
        </dependency>

    </dependencies>


2. TestSample.java class file is the sample setup of selenium test case
3. It includes how to setup the property, create a new instance, visiting google and finding the text input element By Name, the entering something for searching and at last submitting it.

&emsp;      there are other ways to find an element, like :

                  By.ClassName
                  By.CssSelector
                  By.Id
                  By.Name
                  By.XPath
<br>

&emsp;      some performing actions in selenium are,

                  sendKeys()
                  submit()
                  click()
                  dragndrop()
                  KeyDown()
                  MoveToElement()

**Inspectiing Elements**
<br>
      Used to identify web element selectors to use in tests<br>
      A crucial step in writing tests


#Succeeding with WebDriver

**Formy Website Url : https://formy-project.herokuapp.com/** <br>

&emsp;&emsp;      A site which contains form components that can be used for testing purpose <br>
<br> Here are the list of all the components

<b> AutoComplete : Buttons : Checkbox : DatePicker : Drag and Drop : Dropdown : Enabled and Disabled Elements : File Upload : <br>
    Key and Mouse Press : Modal : Page Scroll : Radio Button : Switch Window : Complete Web form. </b>
      
Let's write some test cases using selenium to test different website's UI.

<h4>Steps to write a sample test case :</h4>

&emsp;<b> 1. import the required libraries or modules like chromedriver, webdriver, webElement etc.<br>
&emsp;    2. start with writing the code byy creating class. <br>
&emsp;    3. create a function with accepting arguments. <br>
&emsp;    4. in that, set the property for webdriver which you are using. <br>
&emsp;    5. the create instance of the chrome driver and then use get function to visit the URL. <br>
&emsp;    6. the write the test case based on the scenario which you want to chek. <br>
&emsp;    7. at last submit the form. <br>
&emsp;    8. and quit from the webdriver. <br>
</b>
    

  
