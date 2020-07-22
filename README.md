# php_smtp_gmail
This allows us to send email from our php webpage to all email service providers. Kindly go through the README file for installation steps


Step 1: Download all the files from here.
Step 2: Extract or move files to htdocs folder in windows and  in unix www folder.
Step 3: Open the file PHPMailer.php and find for the field $Username = 'XXXXXXXXXXXXXXX@gmail.com'; and $Password = 'XXXXXXXXXXXXXXXXXXXXX';
Step 4: Replace with your email and password [gmail].
Step 5: Then click this link " https://myaccount.google.com/u/0/lesssecureapps "  - Turn on the less secure apps, then only we can use gmail service via php.
Step 6: Open any browser and type : localhost/FOLDER_NAME/src/mail.php . Then we get a success message if the mail sends successfully. 
        Eg : in my case : http://localhost/phpmail/src/mail.php
                Output : Email sent successfully

``Happy Coding``
``Anurag Kadakkal``
``anuragkadakkal@gmail.com``