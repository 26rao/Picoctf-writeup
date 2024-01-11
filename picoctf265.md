# LOCAL AUTHORITY

This challenge comes under the category of WEB EXPLOITATION, and it was quite easy. We were provided with the link to a particular website [http://saturn.picoctf.net:59126/](http://saturn.picoctf.net:59126/) .The website asked us to provide username and password .But we don't have any, So I opened the source code and noticed that it was in the HTML format later typed the same link using .php extension which gave me access to the source code. The code contains access to a file named "Secure.js" .This file helps us to find username and password.Using the password provided we can easily login and get the flag.I have also attached screenshots for above mentioned explanation.

![](RackMultipart20240111-1-obpobh_html_387e251fd92b7b88.png)

![](RackMultipart20240111-1-obpobh_html_786ec98f1ec75fdb.png)

![](RackMultipart20240111-1-obpobh_html_5d8ee2db558d7b97.png)

# Basic mod1

"We found this weird message being passed around on the servers, we think we have a working decryption scheme.

Download the message here.

Take each number mod 37 and map it to the following character set: 0-25 is the alphabet (uppercase), 26-35 are the decimal digits, and 36 is an underscore.

Wrap your decrypted message in the picoCTF flag format" was the description

On opening the message file, I received a series of numbers as shown below

![](RackMultipart20240111-1-obpobh_html_b7952b72c3c0f92e.png)

Then I created a python file to display the FLAG. The code was successful and I got the flag.The steps ,which I have followed is shown below:

![](RackMultipart20240111-1-obpobh_html_a112c6da4a3a710e.png)

![](RackMultipart20240111-1-obpobh_html_41f29fccee09b090.png)
