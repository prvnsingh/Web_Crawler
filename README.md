# Web_Crawler
Web_crawler bot spider

# Multi-threaded website crawler written in Python
This is a tool to gather all the hyperlinks of a webpage.
This could be modified to do web analytics and webscraping.

# main.py
It contain the main multithreading functions like creating job queue and allocating jobs to individual threads or spider.

# spider.py
It contain the Spider class which has all the attributes required like crawled links, queue links , base url , page url, etc.
It basically decode webpage into string and call the Linkfinder function which gives all the hyperlinks. It then updates all the files.

# Link_finder.py
It checks for anchor ('a') tag with attribute 'href' in the feeded html string given by a spider thread and stores all the links in a txt file which contain the domain name.

# domain.py
This is used to get the domain name from a url.

# utility.py
This contain all the utility functions like creating new txt file, writing into files, converting files to set and set to file, etc.
