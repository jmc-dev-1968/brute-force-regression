
### What is this repository for? ###

* this repo is demo project for UNESCAP in response to a current opening : Statistician (6-STT-ESCAP-54478-R-BANGKOK(G))

* The project entails scraping [UNESCAPS's Statistical Database](http://www.unescap.org/stat/data/statdb/DataExplorer.aspx), which contains ~1000 statistical indicators collected from 58 countries. The data is then ingested into a database, and regression analysis is performed on all pairs of indicators. The project uses the following technologies :

  * C#, used to scrape the data, transform the returned JSON and insert into a MS SQL Server database
  * MS SQL Server, used to store the data as well as create some helper stored procedures used by R
  * R, used to perform a "brute force" regression analysis (every pair of indicators, with some limitations)

 * Project summary and findings found in /docs/Brute Force Regression - Jeffery M. Cooper.pdf
