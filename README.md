# DZ-Univ-Data

## Description

A Dataset for Algerian Universities, Institues, and College Centers. Name in Arabic, French, English, Web site and Region, are the collected Data.

## Notes

### Be Aware

> Last Modification Date

The Data goes to ***18 April 2020***, and it has never being modified or updated since.

> UTF-8

The data in the Json files are encoded in the UTF-8 standard, so read the files contenent using a programming language and not just by a text editor, because of the Arabic and French special caracters.

### Resources

The are the following recourse used to collect end combine the Data.

* Official Government websites:
  * <https://www.mesrs.dz>

### Scraping code

This work belongs to [Herhar Fares](https://github.com/FaresHerhar), and if you are looking for the Scraping code, please visit the [club-collect](https://github.com/FaresHerhar/club-collect) repository.

## Explaing the Data

The same data was stored in CSV files and JSON, in which each there is 4 files but duplicated (a CSV and a JSON version).

> The Data is structered as fallows

```json
university:{
  "web_site":"The web site of the university",
  "name_ar":"The name of the university in Arabic",
  "name_fr":"The name of the university in French",
  "name_en":"The name of the university in English",
  "region_ar":"The region of where ths university is located (east, center, west), in Arabic",
  "region_fr":"The region of where ths university is located in French",
  "region_en":"The region of where ths university is located in English"
}
```

> Explain The Data: The same file duplicate contains the same Data, but in a different representation

* univ.json, univ.csv: Contains Data about the Algerian Universities.
* schools.json, schools.csv: Contains Data about the Algerian National Institues.
* teach.json, tech.csv: Contains Data about the Algerian National Teachers Institues.
* center.json, center.csv: Contains Data about the Algerian University Centers.
