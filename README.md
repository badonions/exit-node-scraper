# exit-node-scraper

Simple Python module for scraping exit nodes from https://check.torproject.org/exit-addresses

## Do it from command line

```
$ curl -s https://check.torproject.org/exit-addresses | grep ExitNode | sed 's/ExitNode //g' > fp.txt
```
