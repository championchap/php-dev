# php-dev

A PHP development environment in Docker.


## Services

  + Nginx
  + PHP
  + MariaDB
  + Redis
  + Adminer
  + Composer
  + NodeJS


## Instructions

  + Clone this repo.
  + `cd` into the root of the repo and run `docker-compose up`.
  + Make a file ./code/public/index.php and put `<?php phpinfo();` in it. Save.
  + Visit `http://localhost` in your browser.
  + Visit `http://localhost/adminer` in your browser for a GUI to the Database. 
  + Set up your DB by putting SQL files in `./database/entry`. These are executed alphabetically on first run (no data directory). 
  + 

## Authors

 - [Erik Watson](mailto:erik@erikwatson.me)
