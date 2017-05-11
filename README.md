# WordPress Workbench
WordPress Workbench is a WordPress starter project. Inspired by Mark Jaquith's [WordPress Skeleton](https://github.com/markjaquith/WordPress-Skeleton) and John P. Bloch [WordPress Project](https://github.com/johnpbloch/wordpress-project).
This package is meant to kickstart your WordPress Development. I highly do not recommend this to be deployed in production server.

## Getting Started

Installing is as simple as:

    git clone git@github.com:edden87/WordPress-Workbench.git my-project
    cd my-project
    composer install

Open wp-config.php and define your mysql settings

    /** The name of the database for WordPress */
    define('DB_NAME', 'YOUR_DATABASE_HERE');
    
    /** MySQL database username */
    define('DB_USER', 'YOUR_USERNAME_HERE');
    
    /** MySQL database password */
    define('DB_PASSWORD', 'YOUR_PASSWORD_HERE');

## Adding WordPress .gitignore:

Depending on your preference you can install a GIST .gitignore.
  
    curl -O https://gist.githubusercontent.com/salcode/b515f520d3f8207ecd04/raw/.gitignore

Or doing it manually

    touch .gitignore

## License

MIT License

