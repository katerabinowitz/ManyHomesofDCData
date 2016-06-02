# ManyHomesofDCData
DC data lives in many different locations in many different formats - it may be on the official DC open data website, (briefly) live on a Dropbox folder for a hackathon, tucked away on an agency website, or an individual's Github. It can be difficult to navigate and even know if the data you want exists. Here's hoping this provides a modicum of clarity, making it easier for people to find the data they need and identify areas where data is needed. This list will also help inform a new Code for DC Open Data Portal. 

Please contribute to the list! You can do so by:
* Submitting an issue
* Making a pull request
* E-mailing me at datalensdc@gmail.com

Or, if you there's particular data you want but don't know where it lives, submit an issue or e-mail me! We can find or FOIA it.

**DC Open Data**
---------------------------------------------------
| Topics   | Agency   |  Summary (and hyperlink)                            | Data Type     |Notes|
| -------- | --------:|----------------------------------------------------:|--------------:|----:|
|Multiple|Multiple|[official open data site](http://opendata.dc.gov/)|API; multiple|mostly geo. highlights include 3+ years of crime, ticketing, crashes and business licenses|
|Multiple|Multiple|[Code for DC open data catalog](https://www.opendatadc.org/)|API; multiple|scraped/FOIA data, slightly dated. We're reviving it!|
|Geography|Multiple|[All the Maps](https://github.com/benbalter/dc-maps)|GeoJSON|by Ben Balter|
|Demographics|Multiple|[Demographics at many different geo levels](http://www.neighborhoodinfodc.org/)|HTML/XLS|population,well-being,housing,foreclosures,schools|
|Education|OSSE|[Best single resource on school data](http://www.learndc.org/)|html, csv|school profiles and performance.Benjamin Robinson created [R package for data](https://github.com/benjaminrobinson/LearnDC)|
|Education|OSSE|[school enrollment audits](http://osse.dc.gov/service/data)|XLSX||
|Education|PCSB|[Charter performance, enrollment, lotteries](https://data.dcpcsb.org/)|API; multiple||
|Education|DCPS|[DCPS school budgets,budgeted enrollment](http://www.dcpsdatacenter.com/index.html)|XLSX||
|Education|DCPS|[enrollment, grad rates, test scores](http://dcps.dc.gov/service/dcps-downloadable-data-sets)|XLSX||
|Transportation|WMATA|[Metro ridership, survey responses](http://planitmetro.com/data)|XLSX||
|Transportation|WMATA|[routes, real time predictions, incidents](https://developer.wmata.com/)|API; multiple||
|Transportation|WMATA|[Metro service disruptions](http://www.wmata.com/rail/service_reports/viewReportArchive.cfm)|html|opendatadc.org has 2012-15. have scraper|
|Transportation|WMATA|[Elevator/escator outage](http://www.wmata.com/rider_tools/metro_service_status/elevator_escalator.cfm?)|html|opendatadc.org has a time series|
|Transportation|DDOT|[2006-2013 bike crash data](http://opendata.arcgis.com/datasets?q=bike%20accidents&t=dc%20bike%20accidents)|API; multiple||
|Transportation|DDOT|[Traffic volume maps, 2002-11](http://ddot.dc.gov/page/traffic-volume-maps)|PDF map with volume notations near street||
|Transportation|DDOT|[DC Bike Count data](https://github.com/HackShopDC/October29-VisionZeroData/tree/master/BikeCountData)|XLS|2002-15 person-led bike counts|
|Transportation|Capital Bikeshare|[station feed, trip history, member surveys](https://www.capitalbikeshare.com/system-data)|XML,csv, pdf||
|Transportation|Arlington County|[automated bike counts in VA, MD, and DC](http://www.bikearlington.com/pages/biking-in-arlington/counting-bikes-to-plan-for-bikes/counter-dashboard/)|XML|have scraper, need to productionalize|
|Transportation|DDOT|[Permits issued by DDOT for use of public space](https://tops.ddot.dc.gov/DDOTPermitSystem/DDOTPermitOnline/Reports/PublicConstructionPermitReport.aspx)|searchable database||
|Food|ABRA|[Liquor License Holders](http://abra.dc.gov/page/abc-licensees)|PDF|Replaced every 6ish months;have two previous copies|
|Food|DOH|[rolling last 3 years food & hygiene inspections](http://dc.healthinspections.us/webadmin/dhd_431/web/)|HTML| have rudimentary scrapper; opendatadc.org has history 2010-2015|
|Crime|MPDC|[Crime 2000-14](https://github.com/UrbanInstitute/occ-public-safety/blob/master/data/dccrime2000-2014_cleaned.csv)|csv||
|Crime|MPDC|[DC Crime Map](http://crimemap.dc.gov/)|csv|searchable database, annual datasets at opendata.dc.gov|
|Crime|MPDC|[DC Crime Stats](http://mpdc.dc.gov/page/statistics-and-data)|html, pdf|citywide crime + traffic fatalities|
|City |DHR|[DC Employee Salaries](http://dchr.dc.gov/public-employee-salary-information)|PDF||
|City||[annual FOIA Report Statistics](http://os.dc.gov/page/annual-reports)|PDF|annual FOIA request counts by agency|
|City|Multiple|[311 Requests](https://dc311.secure.force.com/)|multiple|Current 311 requests on the last 30 days map. opendata.dc.org has last 30 days datasets for request types. 2010-13 on opendatadc.org|
|City|Council|[Legislative information](http://lims.dccouncil.us/api)|JSON|information about bills, resolutions, contracts and reports submitted to the Council|
|Building|DCRA|[Certificate of Occupancy](https://github.com/katerabinowitz/ManyHomesofDCData/tree/master/Certificate%20of%20Occupancy%20Data_Hackathon)|XLSX|released during GS hackathons| 
|Building(ish)||[AirBnB](http://insideairbnb.com/get-the-data.html)|CSV|scraped October 3, 2015|
|Budget|OCFO|[7 years of DC budget visualized](https://openbudget.dc.gov/transparency#/)|HTML|maybe if you create an account you can download the raw data?|
|Budget|OCFO|[DC Capital Improvement Plan, 2010-15](https://github.com/cmgiven/capital-improvement)|XML/JSON|scraped by Chris Given!|
|Budget|DMPED|[Great Streets Grantees](https://drive.google.com/file/d/0B7P0PQCxjXdsajJIa3c4ampiOEU/view)|csv||
|Environment|DOEE|[Air Quality Data](http://www.mwcog.org/environment/air/data/)|HTML||
|Environment|DOEE|[Water Quality Data](https://stormcentral.waterlog.com/public/dcwater)|HTML|River, not drinking, water|

**Federal Open Data**
---------------------------------------------------
| Topics   | Agency   |  Summary (and hyperlink)                            | Data Type     |Notes|
| -------- | --------:|----------------------------------------------------:|--------------:|----:|
|Science|NIH|[ExPORTER: abstracts of all funded grants](http://exporter.nih.gov/ExPORTER_Catalog.aspx?sid=3&index=1)|XML,CSV|Patents,publications and clinical studies too, but these are incomplete|

