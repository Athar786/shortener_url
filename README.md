# shortener_url
URL Shortener in Laravel 8

git clone https://github.com/Athar786/shortener_url.git

step - 1 : composer install
step -2 :  cp .env.example .env
step - 3 : php artisan key:generate
step -4 : php artisan vendor:publish --provider="AshAllenDesign\ShortURL\Providers\ShortURLProvider"
Step-5 : php artisan migrate
