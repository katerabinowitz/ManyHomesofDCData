# ManyHomesofDCData
Don't let opendata.dc.gov fool you, DC open data lives in many corners of the internet. Here's an (in)complete list.

Please contribute to the list! You can do so by:
* Submitting an issue
* Making a pull request
* E-mailing me at datalensdc@gmail.com

**DC Open Data**
---------------------------------------------------
| Topics   | Agency   | Link                          | Summary                                             | Data Type     |Notes|
| -------- | --------:|------------------------------:|----------------------------------------------------:|--------------:|----:|
|Multiple|Multiple|http://opendata.dc.gov/|official open data site|API; multiple|mostly geo but also 3+ years of crime, ticketing, crashes and business licenses|
|Multiple|Multiple|https://www.opendatadc.org/|Code for DC's current open data catalog|API; multiple|scraped/FOIA data, dated. We're reviving it!|
|Education|OSSE|http://osse.dc.gov/service/data|school enrollment audits|XLSX||
|Education|PCSB|https://data.dcpcsb.org/|performance, enrollment, lotteries, etc|API; multiple||
|Education|DCPS|http://www.dcpsdatacenter.com/index.html|DCPS school budgets,budgeted enrollment|XLSX||
|Education|DCPS|http://dcps.dc.gov/service/dcps-downloadable-data-sets|enrollment audits, graduation rates, Comprehensive Assessment System scores, SAT scores|XLSX||
|Transportation|WMATA|http://planitmetro.com/data|Metro's planning blog, one-off data downloads;
ridership, survey responses|XLSX||
|Transportation|WMATA|https://developer.wmata.com/|routes, real time predictions, incidents|API; multiple||
|Transportation|WMATA|http://www.wmata.com/rail/service_reports/viewReportArchive.cfm|daily service report; archive of daily Metro service disruptions|html||
|Transportation|WMATA|http://www.wmata.com/rider_tools/metro_service_status/elevator_escalator.cfm?|Elevator/escator outage|html|opendatadc.org has a time series|
|Transportation|DDOT|http://opendata.arcgis.com/datasets?q=bike%20accidents&t=dc%20bike%20accidents|2006-2013 bike crash data|API; multiple||
|Transportation|DDOT|http://ddot.dc.gov/page/traffic-volume-maps|Traffic volume maps, 2002-11. |PDF map with volume notations near street||
|Transportation|DDOT|https://github.com/HackShopDC/October29-VisionZeroData/tree/master/BikeCountData|DC Bike Count data|XLS||
|Transportation|Capital Bikeshare|https://www.capitalbikeshare.com/system-data|station feed, trip history, member surveys|XML||
|Transportation|Arlington County|http://www.bikearlington.com/pages/biking-in-arlington/counting-bikes-to-plan-for-bikes/counter-dashboard/|bike counts in VA, MD, and DC|XML|have scraper, need to productionalize|
|Food|ABRA|http://abra.dc.gov/page/abc-licensees|Liquor License Holders|PDF|PDF replaces itself every 6 months;  have two previous copies|
|Food|DOH|http://dc.healthinspections.us/webadmin/dhd_431/web/|last 3 years food & hygiene inspections|HTML|provides 3 years of inspections from current date. have a rudimentary scrapper; opendatadc.org has history 2010-2015|
|||https://dc311.secure.force.com/|311 Requests|arcGIS|Current 311 requests live on the last-30 days-map. 2010-13 on opendatadc.org|
|City |DHR|http://dchr.dc.gov/public-employee-salary-information|DC Employee Salaries|PDF||
|Budget|OCFO|https://github.com/cmgiven/capital-improvement|DC Capital Improvement Plan, 2010-15|XML / JSON|scraped by Chris Given to csv!|
