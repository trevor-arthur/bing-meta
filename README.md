# Shodan API CLI
*Made by: Trevor Arthur*

**bing-scraper** collects files with a certain extension from a target site. If the files are Microsoft Office files, bing-scraper also gathers the metadata from the file.

### How to Use:

	git clone https://github.com/trevor-arthur/bing-scraper

	cd ./bing-scraper/client && go build -o bing-scraper

	./bing-scraper <website> <extension>

Example:

	./bing-scraper va.gov docx
	
