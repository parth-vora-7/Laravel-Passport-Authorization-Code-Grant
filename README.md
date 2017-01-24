<b>Follow these steps:</b>

1) Clone the repo using git clone https://github.com/xparthx/Laravel-Passport---Oauth2.git

2) cd passport

3) php artisan migrate

4) php artisan serve

5) Visit http://localhost:8000/register and create a new user and then log in

6) Create a new OAuth Client by clicking on "Create New Client" link

7) Grab the Client ID and Secret of the client you just created

8) Replace "client_id" and "client_secret" with the Client ID and Secret which you got in step 6 in consumer/routes/web.php file

9) cd consumer (in new terminal)

10) php artisan serve --port=9000

11) Visit http://localhost:9000/redirect

12) Login into the site(http://localhost:8000/) using the user you just created

13) Autorize the app and you will get all the user information of the user you are logged in with
