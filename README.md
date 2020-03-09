# codesample-python-scrapy-old-example
Old Example of Python Scrapy
Depends on Scrapy module for Python 2.7 Using Python 2.7 because Scrapy stable package available for Python 2.x for now

Scrapy installation (based on https://linoxide.com/ubuntu-how-to/scrapy-install-ubuntu/):

(optional, mandatory only if not installed) install pip: sudo apt-get install python-pip
(optional, mandatory only if not installed) install development libraries: sudo apt-get install python-dev
(mandatory) intall Scrapy module itself: sudo pip install scrapy
How to run?

cd oldPythonScrapySpiderExample
scrapy crawl FaragovfirstpageSpider -o /path/to/scrapyOutput/output/output.json
