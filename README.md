# Downloader for Media Attached to Public Tweets

This is a Python script that will download photos and videos attached to public tweets matching a specified search term or set of search terms. 

Usage
* Specify queries in the UI with a comma separating each term
* Enter the value in seconds for the interval to wait between searches
* Specify an output directory
* Click 'Download' to execute an initial search and start the schedule for executing searches

Example:
* #test,#another_test,#thirdtest,hello-world

Notes
* It only downloads up to 100 tweets at a time
* You must create a Twitter developer account, create your own application, and supply the following values if you want to run this yourself: ACCESS_TOKEN = '', ACCESS_SECRET = '', CONSUMER_KEY = '', CONSUMER_SECRET = ''
* Save the file names of media files you do not want to download in the blacklist.txt file. Input each file name as a new line in the blacklist file.
