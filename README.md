# CrawlerApp
Crawler Application is a simple crawler application (Console Application) allows to Crawl a paths of a given website using [Symfony](https://symfony.com/) framework and Spatie\Crawler library.

# Before starting
1) First of all, download this console application and make it inside HTDOCS folder and run the XAMPP server.

2) The limited crawling number is 20 , and you can change this number using `src/Crawler/Commands/CrawlerCommand.php#setMaximumCrawlCount()`.

3) You should enter a valid website link, for example : "https://www.linkedin.com".

# Use of CrawlerApp application
1) Open the command line and go to `CrawlerApp` folder, after that run the Symfony server using this command :             
`php bin/console server:run`

2) Type this command line to start the application : `php bin/crawler start`

3) After that it will show you this message _"Please enter a valid website link with 'https://' :"_ , so you should enter a valid website link with "https://" , and press ENTER.

4) Finally, you should see the result in the command line. In addition to that you can see it also inside a JSON file located on the main folder of CrawlerApp application named `crawler json result.json`.
