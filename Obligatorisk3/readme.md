#IMPORTANT

**.ENV**
DB_DATABASE=giveaway *This is the only thing you need to create in mysql in order for the
							code to work. Just create a database called giveaway in mysql*

DB_USERNAME=root *Edit this to your chosen username*

DB_PASSWORD= *Edit this to your chosen password*













--------------
#NOT IMPORTANT
--------------
**.ENV**
MAIL_DRIVER=log *If a user have forgotten his passwords and needs a new one sent to his mail,
						the link is not sent to his mail but added to storage/logs/laravel.log
						- You can just copy the link from this file and paste it to your browser in
						order to change your password*
