# Kasada

## What is Kasada?
[Kasada ](https://www.kasada.io/ "Kasada") is one of the new anti-bot solution on the market.

## Our View on Kasada

### How to Identify Kasada
Unluckily [Wappalyzer Chrome Extension](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/0386528f99a1209a538f6d042e859cd9933011c8/Pages/Tools/Wappalyzer.md) does not work in this case but the websites protected with this solution have a peculiar behaviour.
The first request to the website returns a 429 error (visible only from the Network inspection in the browser's developer tools), then redirect to the same page that works properly. This second request added some elements in the response headers like "x-kpsdk-ct"

### Recommended approach to Kasada
**BEST CHOICE**: at the moment, the best approach is a [Playwright](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Playwright.md) using Firefox with the right flags. 

### How yo bypass Kasada according to The Web Scraping Club
[Posts about Kasada](https://substack.thewebscraping.club/t/kasada)

### Reference and interesting links
[Official web page](https://www.kasada.io/)

