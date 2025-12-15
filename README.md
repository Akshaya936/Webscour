# WebScour – Python Web Crawler

A simple, domain-restricted web crawler built using Python.  
The crawler starts from a seed URL, fetches pages, extracts links, filters them, and crawls additional pages.  
All downloaded pages are saved locally in the `pages/` directory.


## Features

- Domain-restricted crawling (avoids external websites)
- BFS-based crawling using a queue
- Automatic HTML saving (`pages/page_#.html`)
- Retry mechanism for failed requests
- Duplicate URL detection
- Clean and modular code structure
- Delay between requests

## Technology
 Language: Python
 Libraries: request, BeautifulSoup, time, os, urlparse



