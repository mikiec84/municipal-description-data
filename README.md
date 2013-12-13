municipal-description-data
==========================

Machine readable (JSON) descriptions of municipal (city) council descriptions for use with opencivicdata/pupa.

See http://docs.opencivicdata.org/en/latest/scrape/new.html and https://github.com/opencivicdata/municipal-scrapers-us. Meant as a way of sharing the data required to scrape and describe municipalities' councils.


#Usage

You can access a municipality's description data by following this convention on the static site:

```
country code/region code/city name with dash separators plus .json extension
```

Codes are two character standard codes. So Albuquerque, New Mexico, USA would be found at this URL:

/us/nm/albuquerque.json

Or Santa Fe

/us/nm/santa-fe.json

Countries where regions (aka states or provinces)  are not relevant can skip them and simply use this pattern:

```
country code/city name with dash separators plus .json extension
```

Until we set up a permanent home, you can get the data by grabbing the raw file off github like so:

https://raw.github.com/opengovernment/municipal-description-data/master/us/nm/albuquerque.json


#Contributing

To contribute municipal description data, fork the repository, and  submit a pull request.
