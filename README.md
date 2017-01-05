# phalcon-php7

To star php run

`docker run -d --name phalcon_project -v "$pwd":/var/www -p 5007:80 sabbir1cse/phalcon:latest`

Where "$pwd" is your current phalcon project root directory. You can expose any port you want publically.
Log file will be generated for phalcon and php erorr and apache access on project root. This is highly recommanded for development purpose.
For production create your own security fixes for php and apache.
