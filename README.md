Thijs Demeester & Melinda Cornette

Installation Laravel Project
Make sure composer and node.js are installed on your machine.

git clone repo
cd
npm install
Open project in editor and goto your Appserviceprovider. Put all variables of count in comments
composer install
Copy .env.example to .env and put all necessary settings inside mail, database, ...
php artisan key:generate
(.env: FILESYSTEM_DISK: local vervangen door public)
Open project in editor and DELETE assets folder completely inside public folder if it exists (public/assets).
php artisan migrate:fresh --seed
In Appserviceprovider uncomment all variables of count.
php artisan storage:link (setting storage link for images)
Start your wamp, mamp or xamp server
Create inside the server your databasename
php artisan migrate:fresh --seed
npm run dev
php artisan serve (then click on localhost)


##That's all folks, application is running.
