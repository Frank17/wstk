# wstk
Just a placeholder for the WSTK (web scraping toolkit) library I'll create next year (i.e. 2023)

---

WSTK (Web Scraping Toolkit) is a highly extensible & customizable yet efficient library that supports a wide range of common tasks seen in web scraping practice. Including but not limited to:

- Respect `robot.txt` by default
- Scheduled crawling (with default timeout/retrying/exception handling)
- Execute JS code
- Optionally retrieve content only after JS is fully loaded
- Pagination mechanism (support both BFS and DFS)
- Packet sniffing & filtering
- Auto-scraping videos in `.m3u8` format
- Bypass font/JS obfuscation + common CAPTCHAs
- Incremental crawling (with website change detection)
  - Additional support to exact diff. percent detection (e.g. respond only if >20% of the content has changed) and other conditions
- Proxy pool
- Distributed & async crawling
- Perform NLP tasks on scraped data
- Optionally save & analyze historical data (date of crawling, URLs visited, # of chars scraped, etc.)
- Emailing system
- ...
