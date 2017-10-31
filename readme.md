#Laravel 5.5 with Jwt Auth

1. composer update
2. Go to JWTGenerateCommand.php file located in vendor/tymon/src/Commands and paste this part of code public function handle() { $this->fire(); }
3. php artisan jwt:generate
