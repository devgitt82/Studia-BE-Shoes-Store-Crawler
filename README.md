﻿# Spider crawler for data extraction from popular shoe store.
 **Part of a shoe store project - 2nd year of studies at Gdansk University of Technology**

**Requirements:**
---

1. [Scrapy](https://docs.scrapy.org/en/latest/intro/install.html#intro-install)
   
**Installation and running:**
---

1. Clone repo to your local host.
2. Change directory to `/shoes/spiders`
3. Run `scrapy crawl [spider name] -O [file name].json ` command. eg. `scrapy crawl produkty.json ` for `json` file output or
4. Run `scrapy crawl [spider name] -O [file name].csv ` command. eg. `scrapy crawl kategorie.csv ` for `csv` file output

