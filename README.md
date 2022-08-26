
![Logo]( https://linkuin.net/public/assets/users/img/Logo.png )



LinkuinSlave 

Linkuinslave is a link promotion site where link website links were promoted.
please follow above steps.

step 1: Go to github (https://github.com/Hatseflatsh/linkuinslave) and clone http url ( https://prnt.sc/B9KAkkPMM_2R )

step 2: Open git bash or windows CMD or terminal and follow as below steps.

Step 3:  clone the repositery 

		- git clone <git url>[ https://prnt.sc/wjRTjzUoQYVP ]
step 4: enter in project folder - https://prnt.sc/Ayuwo1MEy-Jt

step 5: run below command to download dependencies of the packages ( https://prnt.sc/sco6l-ZlGNbG )

		- composer install
step 6: Now, generate the .env file and key for it using the below commands ( https://stackoverflow.com/a/29915688 )

		- cp .env.example .env
		- php artisan key:generate
step 6:  Make the following changes in the .env file.

        APP_ENV=local
        APP_KEY=base64:NyYHhAy3A5eSq0AKOO5gp7KCT+XAx0UZlXYMCI8VkMU=
        APP_DEBUG=true
        APP_URL=<your url> (ex: https://linkuinslave.nl/)
        ASSET_URL=<your asset url>(ex: https://linkuinslave.nl/public)
        API_URL=https://linkuin.net/api/

        MAIL_MAILER=smtp
        MAIL_HOST=smtp.gmail.com
        MAIL_PORT=465
        MAIL_USERNAME="devsvpt.narola@gmail.com"
        MAIL_PASSWORD="lbtbyqflatmhqmzp"
        MAIL_ENCRYPTION=ssl
        MAIL_FROM_ADDRESS="no-reply@linksbuilding.com"
        MAIL_FROM_NAME="${APP_NAME}"



		Note : Here in .env file You only have to change APP_URL, APP_KEY, ASSET_URL, MAIL_MAILER, MAIL_HOST, MAIL_PORT, MAIL_USERNAME, MAIL_PASSWORD, MAIL_ENCRYPTION. 
		please refer as above example for env file changes


