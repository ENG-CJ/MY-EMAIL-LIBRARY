# MY-EMAIL-LIBRARY
I've Developed this library that is used for email services like sending emails . this compatible only csharp language, add to your csharp projects for free <br>
# How to Add This File Into Ur Project
First download this file then follow steps below.<br>
1. Right Click Folder of your CSharp project<br>
2. Click Add references<br>
3. Click browse and then select <kbd>DLL</kbd> File  named <kbd>Cj_Delivery_Email</kbd><br>
4. Then Click Ok 

# How to use by code 
if you already adding this file to your references folder then follow steps below<br>
1. Import NameSpcae of Libray by using this syntax  <kbd>using cj_Delivery_Email.Email</kbd><br>
  :: ::  Cj_Delivery_Email is a nameSpcae also .Email is another nameSpace belongs to the Cj_Delivery_Email<br>
2. create the instance of my Email Library by using this syntax <kbd>MyEmail email = new MyEmail();</kbd>
3. Your Create empty instance means no arguments also you can pass required arguments <kbd>I Recomended To pass arguments to the instance
when you create the instance<br>
MyEmail Lib has 3 instance, one is default constructor, another one takes 2 arguments and another takes 4 arguments we use the one that takes 4 arguments<br>

by using this Code 
```java
using Cj_Delivery_Email.Email;


MyEmail email = new MyEmail(
"Your Gmail address",
"Your Password",
"From Gmail Address",
"To Gmail address"

);

email.SendEmail("DisplayName","Email Subject", "MessageContent");
```
 <br>
 You can use this code by sending email using my library. 

Note : if you ommit arguments in <kbd>sendEmail() method</kbd> this method has default arguments and the lib will send your email followed by these default arguments
, so Provide your custom arguments like :: Dispayname, Subject , Mail-message ::

# Compatible
This lib Only Compatible C# apps like
> Winform Apps <br>
>  Asp.net  <br>
> Console Apps 

# Author 
Email : abdulrahmandev10@gmail.com<br>
Mobile : 683533247
