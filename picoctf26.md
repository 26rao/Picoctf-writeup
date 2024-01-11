# CAAS

At the beginning of the game, I was given access to a site called _COWSAY AS_ _A SERVICE_ .

On opening the link I was directed to a page as shown below,

![](RackMultipart20240111-1-uxxy7z_html_cac5eb7c919995df.png)

Copying the link address, I used visual studio code to understand the source code of the page. Since this deals with web exploitation I couldn't find anything much useful. Then I googled web tools and installed _burp suite application_ where I inspected the source code tried editing the message into some random name called _mooh_ to check whether it .I found that it doesnot have any impacts on it Then I used cat command to retrieve the necessary data and finally captured the flag.

![](RackMultipart20240111-1-uxxy7z_html_b0e703ff383c7ceb.png)

![](RackMultipart20240111-1-uxxy7z_html_d11c95cdb129f67a.png)

# FORbiddden path

In this question we were given a kind of hint or idea about the game

"We know that the website files live in /usr/share/nginx/html/ and the flag is at /flag.txt but the website is filtering absolute file paths." Using any kind of username didn't provide us access to the site.

![](RackMultipart20240111-1-uxxy7z_html_1798e6277d150f0b.png)

![](RackMultipart20240111-1-uxxy7z_html_f73a2ec8eb62f7fb.png)

Finally using this username (given in the image below) gave access to the flag

![](RackMultipart20240111-1-uxxy7z_html_9d29e5bb33adfd32.png)

![](RackMultipart20240111-1-uxxy7z_html_54902f2f7ea67e99.png)

####
# T

# unn3l v1s10n

The description says that we have been provided with a file and hint says _that the data is weird and its wont display right._

_So I opened the file on notepad and found it in some other format since it was a bitmap file .So isaved it using extension .bmp but I couldn't load the image ;so once again I used hex editor( keeping in mind the bitmap format )I edited it and reloaded the image and I was able to see the code_

![](RackMultipart20240111-1-uxxy7z_html_ec37a1d97596fecc.png)

![](RackMultipart20240111-1-uxxy7z_html_b7acf6ee87033728.png)

## KEYGENME-PY

30 points keygenme -py was not that bad .Here we were given a code file.After going through the file I came across certain key texts; to recollect them I created a new python file on visual code and since I didn't have compiler I used online and compiler and found the output.

![](RackMultipart20240111-1-uxxy7z_html_148c7b782e27a108.png)

![](RackMultipart20240111-1-uxxy7z_html_20a9354fce9d2c3a.png)

## Buffer overflow

The program was given and link to its source was also provided. Initially I checked the file type ; since it was a binary exploitation challenge the file was a binary file.So here in order to smash the file we need use bunch of some characters .Here on using 'A's I was able to crack it.

![](RackMultipart20240111-1-uxxy7z_html_e0e4a6c6c6fceb44.png)
