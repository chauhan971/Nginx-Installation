# Nginx-Installation
This Repository will help you with the step-by-step installation of Nginx on Linux and running a html file on localhost

<h2>Install Nginx</h2>

Installation command for Nignx

````
sudo apt update
sudo apt nginx
````
<h2> Find the default website Root </h2>
<p> The default website root Ubantu is  <b>/var/www/html</b> </p>

``
cd /var/www/html
``
<p>
  After moving to the website root try " ls " command to check for the index.html file present in it
  If you donot have index.html file no worry just create a file file </p>
  
 <h2> Creating Index.html </h2>
 
 ``
 sudo nano index.html
 ``
 
 <h2> Html Code </h2>
 <p> Write the html code to the file as per per your need how you want your page to look like</p>
 
 ``
 #<!DOCTYPE html>
 <html>
 <body>
 
 <h1>My website is live on NGINX!</h1>

 <p>Hello World!</p>

 </body>
 </html>#
 ``
 
 <h2> Localhost </h2>

