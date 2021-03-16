## How to use

- Clone the repository with __git clone__
- Open the file .env__ and edit database credentials there
- If running locally then name of MySQL database is set to "recurring". So make a new database with the same name using phpmyadmin and run the commands given below to migrate and seed the tables.
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL and login with credentials __admin@admin.com__ - __password__ 

---

