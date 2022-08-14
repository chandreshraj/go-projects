# GO lang
## Basic HTTP service:

Build a simple http server that returns "hello world"
Build a cli that makes an http request to your http server.
Modify the server to return some sort of json object.
Modify your cli to parse the new json object.
Rework both to support gRPC instead of raw http.
This is just an idea, but it exposes you to several aspects of Go that I think are useful (command line tools and web services).

## Advanced ToDo app ( implementing checklist, alerts, priority lists etc)

## Backend Server ( implementing CRUD API operations on SQL/ NoSql DB )

## System Monitor ( implementing graphs, UI, monitoring system resources )

## File / Disk Manager ( summarizing files and folders with your own UI, simple create, delete operations)

## Discord, Twitch, Telegram Bot.

## URL shortener

## ray tracer with an HTTP API 

## dockerizing GoLang apis

## scraper for eBay

## Write a time tracker cli program that can track timestamps for a subject (for example when you had coffee)

  can track periods of time (how long did I work today?)
  persists that data to a file
  reads the data file when the command is invoked
  You can take this as far as you want:
  write to some remote destination (such as an AWS S3 bucket) instead of a file
  encrypt the data file at rest
  write a fancy terminal UI

## A web crawler


## References
 - I used goquery as I feel like it gave me more control than Colly. If you're interested: https://github.com/samjmckenzie/ebay-monitor
 - You can use Colly together with goquery.https://benjamincongdon.me/blog/2018/03/01/Scraping-the-Web-in-Golang-with-Colly-and-Goquery/
- ```
  https://gophercises.com/
  ```   
