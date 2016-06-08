<h3> Create Project : </h3>
------------------------------
composer create-project laravel/laravel folder_name

<h3> Genarate encription key </h3> 
-------------------------------
php artisan key:generate


<h3> Install Migration (First have to configure database) </h3> 
------------------------------
php artisan migrate:install

<h3>  Make new migration </h3> 
------------------------------
php artisan make:migration create_tabelName_table <br/>
OR => php artisan make:migration create_tabelName_table --create=table_name  <br/>

<h3> Run Migration </h3> 
------------------------------
php artisan migrate

<h3>  Create new Controller </h3> 
--------------------------------
php artisan make:controller ControllerName  <br/>
php artisan make:controller ControllerName --resource  <br/>
php artisan controller:make ControllerName --only=index,show  <br/>
php artisan controller:make ControllerName --except=index  <br/>

<h3> Create new Model </h3> 
--------------------------------
php artisan make:model Employee  <br/>



