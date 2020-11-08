<p style="text-align: center;">&nbsp;</p>
<p style="text-align: center;">&nbsp;</p>
<p align="center"><strong><img src="https://media.dhakatribune.com/uploads/2016/11/nsulogo.jpg" alt="" width="307" height="172" /></strong></p>
<p align="center"><strong>North South University</strong></p>
<p align="center">Department of Electrical &amp; Computer Engineering</p>
<p align="center"><strong>Project Proposal</strong></p>
<p align="center"><strong>Fall 2020</strong></p>
<p align="center"><strong>Project Name</strong>: HOMEMADE FOOD DELIVERY SERVICE</p>
<p align="center"><strong>Course No</strong>: CSE 486 <strong>Sec</strong><strong>:</strong> 1</p>
<p align="center"><strong>Faculty</strong>: Shaikh Shawon Arefin Shimon (Sas3)</p>
<p align="center"><strong><u>Member </u></strong><u>:</u></p>
<p align="center"><strong>Name</strong><strong>:</strong> Toufique E Joarder</p>
<p align="center"><strong>ID</strong><strong>:&nbsp; </strong>1632101042</p>
<p align="center"><strong>Email</strong><strong>:</strong> <a href="mailto:toufique.ejoarder@northsouth.edu">toufique.ejoarder@northsouth.edu</a></p>
<p align="center"><strong>Git Repository</strong><strong>: </strong><a href="https://github.com/NSU-FA20-CSE486-1/1632101_FA2020_CSE486.1/">https://github.com/NSU-FA20-CSE486-1/1632101_FA2020_CSE486.1</a></p>
<p align="center"><strong>Date Prepared</strong><strong>: </strong>08-11-2020</p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>INTRODUCTION</strong></p>
<p>In Dhaka and other Cities/towns in Bangladesh - food catering for office goers and events are a big issue. For health concerns, more and more people prefer lunch meals and event catering from home chefs.</p>

<p>This business need has given rise to many solutions like FoodTong (https://foodtong.co/) , which provides a digital service to connect home chefs with different customers, and use a foodpanda/grubhub like service for home-cooked meals. </p>

<p>Your objective is to develop one single food ordering platform app that serves both chefs and the customers. Customer and chefs/vendor will be able to login from the same app (as different users). </p>

<p>A chef can register as a home-cooked meal vendor, giving his venture a business name - set/update his food offerings; update which meals are going to be offered on which dates. Usually for a home-cooked meal delivery service, the chef decides the night before on what’s going to be available the next day. He or she can set the next day’s availability for an existing item, use the existing item to create a variant for the next day (and it will be stored in the local database as a variation), or offer an entirely new item for the next day (which will also be stored in the database). For each item - a picture is a must. Along with description, items, price, possible discount, coupons etc. For each chef - a location is must, so that customers can look at the nearest vendors first. </p>

<p>For a customer, he or she should be able to see all vendors, and filter them according to item general categories (Meat, Veg) or Specific Categories (Polaw, Biryani) etc. Vendors are typically sorted by the distance from the customer. Customers can order from one or multiple chefs. Customers should also be able to set a monthly meal plan or order catering from the application. </p>

<p>Assume payment is through BKash. When you order, you will enter a 10 digit unique Alphanumerical code (Say 7JQ4GDLLXU) as your BKash payment confirmation code. Traditionally, this code is generated when you transfer BKash money to a particular number. In the order screen, when you have finalized your payment - and clicked on Order now - a screen will appear where you have to enter this alphanumeric code, and instructions to BKash the money to a number. After you have transferred money to this number using Bkash (you dont have to integrate BKash APIs), the 10 digit unique Alphanumerical code (Say 7JQ4GDLLXU) will be generated. You will enter the alphanumeric code as a confirmation for your payment instructions. Your platform will keep 7% of your payment as processing fee, and wire the rest of the money to the food vendors. </p>
{%
<p><strong>FEATURES</strong></p>
<ul>
<li>Easy signup process using the student&rsquo;s NSU email address</li>
<li>An alumnus can also signup using their NSU ID or grade sheet &ndash; this will verified by the Admin Panel</li>
<li>Customizable profile &ndash; an alumnus can update their profile photo, basic information and contact information</li>
<li>Bulk SMS can be sent</li>
<li>News section &ndash; latest news regarding NSU will be shown</li>
<li>Connect &ndash; an alumnus can choose to stay connected with another alumnus to share personal information and get daily updates from one another</li>
<li>Real- time chat</li>
<li>Alumni can be searched using company names</li>
<li>Auto suggestion assistant &ndash; this enables fast search results of companies</li>
<li>Admin Panel &ndash; the admins will have full control over the whole system adding/updating company names and/or updating other information</li>
</ul>
<p><strong>TECHNOLOGY</strong></p>
<p>We decided to go with latest technologies for developing this application in order to give users a better experience.</p>
<p>&nbsp;</p>
<p><em>Frontend</em></p>
<p>For the front end we will be using HTML, CSS, JavaScript and React. This enables cross platform development which allows the web app to be compatible with both PC and mobile platforms. It also gives a more premium user interface and smoother experience.</p>
<p><em>Backend</em></p>
<p>Python&rsquo;s web framework - Django will be used as the website&rsquo;s backend. Django ensures rapid development providing high security and maintanence.</p>
<p><em>Database</em></p>
<p>We will be using MongoDB as the database. MongoDB uses JSON or BSON documents to store data and provides high performance, availability and automatic scaling.</p>
<p><em>Payment method</em></p>
<p>Python&rsquo;s Stripe Library will be used for collecting payments. This API is designed with python and allows custom ways to take payments &ndash; Credit cards, Gift cards etc. We will be using this API to ensure that users can pay using their Visa Cards and MasterCards.</p>
<p><em>Additional technologies</em></p>
<p>Allauth for Django will be used to allow users to login using their Facebook and/or Google account.</p>
<p>We will integrate a real-time chatting system using Django &ndash; Channels within the website.</p>
<p>To keep up with the modern forms of technology we would be using additional technologies to ensure complete user satisfaction. GraphQL is a query language which will act as a bridge between the server-side and the client-side. It provides a faster and efficient way of pulling data from the database.</p>
<p>&nbsp;</p>
<p><strong>Monetization</strong></p>
<p>As the web application is targeting the alumni &amp; authority of North South University, we will try to get fund from the university.</p>
<p>Companies can also place ads on the NSU Alumni Portal for jobs charging 100 BDT per day. We will provide an advertisement package for such companies. As we are integrating the stripe library, making payments for any users will be easy and secured.</p>
<p>&nbsp;</p>
<p><strong>Alternate Approach</strong></p>
<p>Django, despite of being one of the best web development framework, does hold restrictions when it comes to real-time processes. It cannot handle real-time processes alone and so, requires additional libraries. This is why we came up with an alternate and more simple solution. Golang is a growing programming language which is excellent in these cases. We have developed a part of the django project using Golang and the real-time portion. Comparing both results, we could safely conclude that indeed Golang would have been a better choice as it creates a more vibrant and faster website. However, as time was limited, we did not go ahead and conduct the entire project in Golang as non of us were yet experienced with the language.</p>
<p>&nbsp;</p>
<p><strong>Database</strong></p>
<p>The database was the trickiest part for a system such as this. We needed something with a graph structure and so, we wanted to implement GraphQL on MongoDB making it an extremely fast, scalable and easily accessable solution. However, due to time constraints and the complexity of designing such a pattern on a huge existing database became rather difficult. We ended up using sql lite,  postgresQL and json objects to handle our entire database. It is not as fast and easily accessed like a graph structured database but it does quite good with the limited data involved.</p>
<p>&nbsp;</p>
<p><strong>Unique Searchbar</strong></p>
<p>We created a huge database of companies with their details on an excel sheet. Using python along with it's popular library - "Pandas" we manipulated the excel sheet to create a json object. This json object contained all the details of the companies and upon searching a company name, it would return the entire details of that company.</p>
<p>&nbsp;</p>
%}