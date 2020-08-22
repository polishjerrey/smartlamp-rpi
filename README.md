# homeStorage-NAS
Network attached storage with PHP, intended to be used on a raspberry pi with a hard drive <br>
Use a raspberry pi to accept and store files through a web server <br>
This is done by creating a apache web server with php, you can host this web server with a raspberry pi<br>
Access the server using the ipv4 adress of your raspberry pi (run command <code>ifconfig</code>)<br>
Find your files by going to <code><i>ip/uploads</i></code> for example <code>192.168.1.67/uploads<br></code><br>
<b>Edit variables</b><br>
You can change the allowed file types by changing the <code>$allowed = array('txt', 'jpg', 'png');</code> and adding different file types<br>
You can change the file end destination by changing the <code>$f_destination = '/var/www/html/uploads/' . $f_name_new;</code>
