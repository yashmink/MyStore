# MyStore
Created Automated Smoke Test Suite for MyStore Project

Tools:
a)	Selenium Web Driver
b)	Java
c)	Cucumber
d)	Intellij IDE

Framework: Behavior Driven Development

Tested Functionalities using automation:
a)     Login to the application
b)     add items to cart
c)     Logout from the application
d)     Re-login to the application
e)     Validate the cart 
f)     Perform checkout 
g)     Payment
h)     Confirm order 
i)     Validate Order

Automation Framework Explanation:
a)     Automation tools: Selenium Web driver, Cucumber framework
b)     Main driver script: Runner.java
c)     Cucumber feature files: SmokeTest.feature, Steps.java
d)     Java files:
e)     Login.java -> contains login page objects locator’s information
f)     shopPortalObjs.java -> contains login page objects locator’s information of automation practice site except login
g)     General. Java -> Mystore application related functions
h)     Commonfunc.java -> common functions 
i)     Output report path: “file: C:/Users/user/IdeaProjects/MyStore/target/MyDirectory/index.html”

Assumptions:
j)     Registered User.
k)     Page validations are working as expected.
l)     There was an issue with the automation demo website which I have used -> once I logout and perform re-login to the application, items get deleted from the cart and cart becomes empty. So, I am unable to run the relogin function of the application and verify items in the cart and place an order using the automation script [but I have still written the code to do this task which is commented for the reference]

 Automation work Flow:
a)     Launch the browser and navigate to the website
b)     Login to the application with valid credentials
c)     Add items to cart
d)     Sign-out from the application (code has been commented)
e)     Re-login to the application with same credentials (code has been commented)
f)     Validate the cart items
g)     Proceed to checkout
h)     Payment
i)     Confirm order
j)     Validate order
k)     Close the browser

