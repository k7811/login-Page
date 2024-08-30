index.html

-created a form that contains input feild ,password ,remember me checkbox and a submit button 
-on click on the submit button login function would come into action 
--login function defined in script tag would perform the functionality of loading and redirectingg into home.html
--setTimeout in index.html is given for the spinner and login succesful msg for time of 2sec ---and in home.html after time of 2sec to redirect to login page

script tag
--contains the eye functionality for visibility of password on click and for hiding on click 
----login function has conditions  for checking email , password ----- spinner , related text msg showing errors and success of login which appear on condition.
email condition
-----/^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/ name should start with either a upper or lower case or digit and @ mail and after '.' the characters should be 2 or more (example:abc@gmail.com)
password length should be greater than or equal to 6.
----api call is done using axios to post data in the given open api link.

#st.css
---styling is applied for the form to appear in middle of body with backgroud image,and media query is applied to it for veiwing compatibility in various devices.
----global colors are defined for easier access and color coding format.
---hover effect is used and on focus different coloring is used and also when incorrect that partcular feild will appear in crimson red indicating error.
-----icons are given styling 
------loader spinner is given styling


home.html


----has home in paragaph tag written in body
-----
script tag
---setTimeout function would redirect it to login page after 2 sec.
------------css styling body  background color is applied and flex is applied for text to appear in center
