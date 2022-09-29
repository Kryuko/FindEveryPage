# FindEveryPage

This software will find every page of a website by giving the home page url.


## Usage

You need composer and at least php 7.4.
After downloading the branch, just type in terminal

    composer install

to download dependencies.
  
Then you need to edit the exec.php file, you can use these settings in the $settings array:

 - baseUrl > string, Url of the website's home page
 - enableLog > bool, enable or not logs after crawling has finished.
 - sleepTime > int, time to sleep every download, in seconds
 - logFileName > string, filename including path where you wan't to put the final json log file.

Then you just need to type in your terminal

    php exec.php
    
To start the software.
