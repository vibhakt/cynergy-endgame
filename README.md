# cynergy-endgame
Endgame is the battle for the title of "Coder of the Season", a semester-end competition

# Title of Project

 Title is -#cleancolony_swatchbharath

## Team Members
1. Vibha k t(vibhakt123@gmail.com)

 ## Problem Statement

Waste segregation and its safe disposal has been a major problem in our city since many years. Our area people are facing problem regarding irregular arrival of the garbage vehicle and many remain unaware of it's arrival. Also it is being found that the waste is not segregated appropriately. As this is the need of the hour a website can be developed to keep a track of the vehicle and other activities related to the maintenance of the particular area as well.
 
The website developed should be mainly able to keep a track of the garbage vehicle and send the notification to the people who have registered in it. This is done based on the provided location of the individual registered. Apart from this there should be other links provided as well for new individuals who want to join, etc.

 ## Proposed Solution

As soon as the website is opened a brief information regarding the website such as need of such kind of website and things like it should not be misused will be displayed. After this various links will be provided that gives solution to the problem.

 Link1- this is the link to join to this movement called #cleancolony_swatchbharath by making teams. If a team already exists in the area then it should automatically make the user a member of that existing team or else let him/her to create a new one. For this the link must request the basic information like name, contact number, address/location, number of people in the house, problem they are facing regarding the garbage disposal and an identity proof.

 Link2- this is the main link of the webpage which sends the notification to the individual's mobile. When clicked on this link it should ask for contact number, their location and list of options as how to send the notification like daily basis or weekly basis, when to be informed,like 10 or 15 mins before it's arrival, etc. These things should be mentioned and the regular terms and conditions should be accepted by the user to get the notification.

 Link3- this link is to send a mail to the higher authorities like corporator or MLA of that area in case if there is any inconveniences caused too often.

 Link4- the team members can volunteer to spread awarness regarding maintenance their surroundings neat and clean by planning different kinds of activities. So this link provides a site to share their thoughts among themselves.


 ## Technologies or  Languages Used

 * HTML
* Html is the simplest language that can be used to develop the website.

 ## Instructions to run the project

 The code for displaying the webpage is shown in which four links are provided and the code to create one of those links is also provided.

## code:
<html>
<Head>
<Title>#cleancolony_swatchbharath</title>
</Head>
<Body>
<P>swatch bharath is one of the wishes of Mahatma Gandhi which hasn't been fulfilled yet. As the citizens of our country it is our responsibility to make his dream come true. In this regard the main step is safe and smart disposal of garbage.</p>
<A HREF ="joinmovement.org.in">click here to join our movement</A>
<A HREF ="notifications.org.in">click here to get the notifications</A>
<A HREF ="mail.org.in">click here to mail the authorities</A>
</Body>
</Html>

##code for creating the form for first link provided

<HTML>
<head>
<title>joinmovement</title>
</Head>
<body>
<form>
<table>
<TR>
   <TD>Name:</TD>
   <TD><Input type="text"Name=Name></TD>
</TR>
<TR>
   <TD>Address:</TD>
   <TD><Input type="text"Name=address></TD>
</TR>
<TR>
   <TD>Contact number:</TD>
   <TD><Input type="text"Name=contact number></TD>
</TR>
<TR>
   <TD>Problem:</TD>
   <TD><Input type="radio"Name=facing any problem regarding garbage vehicle"value="yes">yes
   <TD><Input type="radio"Name=facing problem regarding garbage vehicle"value="no">no
</TR>
<TR>
   <TD ALIGN ="Right"><Input type="Button"value="submit"></TD>
   <TD ALIGN ="Left"><Input type="Button"value="cancel"></TD>
</TR>
</Table>
</form>
</body>
</HTML>
