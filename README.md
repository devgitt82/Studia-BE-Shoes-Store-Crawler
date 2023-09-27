# Spider crawler - pozyskiwanie danych ze sklepu z butami
 **Projekt z przedmiotu Biznes Elektroniczny realizowany na 2 roku studiów**

**Requirements:**
---

1. [Scrapy](https://docs.scrapy.org/en/latest/intro/install.html#intro-install)
   
**Installation and running:**
---

1. Clone repo to your local host.
2. change directory to `/shoes/spiders`
3. Run `scrapy crawl [spider name] -O [file name].json ` command. eg. `scrapy crawl produkty.json ` for `json`` file output
   or `scrapy crawl [spider name] -O [file name].csv ` command. eg. `scrapy crawl kategorie.csv ` for `csv`` file output

