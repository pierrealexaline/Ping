# Ping, a simple php /cUrl class to ping a distant url 
   
A simple class to Ping a distant url with PHP.

## Required : 

php 7 + Curl pre-installed
Tested on Ubuntu 16.04 ->19.10


## Example / usage
        require('Ping.php');
        $pg = new Ping();
        $pg->getPing('https://www.infocarto.fr', 3500);
        $pg->getHttpCodeHR($pg->pingR['httpCode']);   
        print_r($pg->pingR);     