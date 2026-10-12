# OSINT-Tools-Ireland
<img src="https://flagcdn.com/ie.svg" alt="Ireland_FLAG"/>
A list of OSINT resources and tools that may be useful to you when conducting investigations related to Ireland. Most of the resources and tools has versions in English and Irish (Gaeilge). Ireland's Central Register of Beneficial Ownership (RBO) is not publicly searchable: full access is limited to competent authorities and designated persons; from 10 November 2026 (S.I. No. 406 of 2026) journalists, NGOs and academics may apply for a legitimate-interest access certificate. CRO company search is free, but filed document images are paid per document. GeoHive is retiring or migrating some of its applications during 2026. Since October 2025 the live Irish aircraft register is only available after sign-in on MySRS; the last public monthly file covers September 2025. Land Registry (landdirect.ie) terms prohibit automated scraping of its data.

**Last Updated:** 2026-10-12

## Contributions
Feel free to join this project — [OSINT For Countries V2.0](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)

## Table of contents:
 - [Open Data portals](#open-data-portals)
 - [Legal Entities](#legal-entities)
 - [Cadastral and other Maps](#maps)
 - [Vehicles](#vehicles)
 - [People, phones, social etc.](#people)
 - [Public procurements](#public-procurement)
 - [WHOIS](#whois)

## Open Data portals
(Country Open Data, Stock Exchange, Courts)
- [data.gov.ie](https://data.gov.ie/data) — Ireland's national open data portal (CKAN): about 22,770 datasets from 141 public-sector publishers; search by keyword, publisher, theme or format; downloads and API. *Lang: EN, GA.* 🏛️
- [CSO PxStat (Central Statistics Office Open Data Statistical Database)](https://data.cso.ie/) — official statistical tables of the CSO, browsable by subject and downloadable; PxStat API and R package (csodata) available. *Lang: EN.* 🏛️
- [Courts Service of Ireland – Judgments](https://www2.courts.ie/judgments) — published judgments of the Supreme Court, Court of Appeal, High Court, Circuit, District, Central Criminal and Special Criminal Courts; search by judgment title (party names) or full text, filter by jurisdiction, neutral citation and judge. *Lang: EN.* 🏛️
- [Legal Diary (Courts Service)](http://legaldiary.courts.ie/) — daily court lists for the Supreme Court, Court of Appeal, High Court, Central Criminal Court and Circuit Court: list number, case number, parties ("X v Y"), legal representatives; updated weekdays at 17:00. *Lang: EN.* 🏛️
- [Irish Statute Book (eISB)](https://www.irishstatutebook.ie/) — Office of the Attorney General database of Acts of the Oireachtas (1922–present), Statutory Instruments (1948–present), Statutory Rules and Orders (1922–1947) and selected pre-1922 Acts; full-text and advanced search. *Lang: EN, GA.* 🏛️
- [Iris Oifigiúil (Official Gazette)](https://www.irisoifigiuil.ie/) — Ireland's official State gazette of statutory and official notices; editions published online. *Lang: EN, GA.* 🏛️
- [Houses of the Oireachtas Open Data APIs](https://api.oireachtas.ie) — parliamentary API: debates, legislation, parliamentary questions, votes (divisions), members, parties, constituencies and houses; JSON responses, XML/PDF files on data.oireachtas.ie. *Lang: EN.* 🏛️
- [Euronext Dublin – Equities list](https://live.euronext.com/en/markets/dublin/equities/euronext/list) — list of shares traded on Euronext Dublin (Irish stock exchange) with ISIN, symbol, market and quotes; ISEQ 20 tab and links to Euronext Growth/Access. *Lang: EN.*

## Legal Entities
- [CORE – CRO Company Search](https://core.cro.ie/) — Companies Registration Office register: free search of companies, limited partnerships and business names by name or registration number; entity details and list of submissions; document images are sold per document. *Lang: EN.* 🏛️
- [CRO Open Data – Company Records](https://opendata.cro.ie/dataset/companies) — daily-updated bulk CSV (zip) of all companies registered with the CRO, including dissolved and closed entities; CC BY 4.0, EU High Value Dataset. *Lang: EN.* 🏛️
- [CRO Open Services API](https://services.cro.ie/) — free REST API for company and submission search (same data as CORE); requires sign-up and signed terms and conditions; document streaming is pay-per-call for account holders. *Lang: EN.* 🏛️ ⚠️
- [Charities Regulator – Register of Charities](https://www.charitiesregulator.ie/en/information-for-the-public/search-the-register-of-charities) — about 11,500 registered charities; search by name, registered charity number (RCN), purpose or county; trustees, employees, annual reports filed, Governance Code compliance; full register downloadable as .xlsx. *Lang: EN.* 🏛️
- [Intellectual Property Office of Ireland – Trade Mark Search](https://ipoi.gov.ie/en/ip-search-tools/trademark-search/) — free online search of national trade marks and international registrations designating Ireland (quick search by number, advanced search; captcha); patent and design search tools on the same site. *Lang: EN.* 🏛️
- [Central Bank of Ireland Registers](https://registers.centralbank.ie/) — official registers of authorised financial service providers (firm search) and collective investment schemes (downloadable lists). *Lang: EN.* 🏛️
- [SoloCheck](https://www.solocheck.ie/) — Irish company profiles built on CRO data: status, registered address, incorporation date, activity code, largest shareholder, aggregate director statistics, list of filings. *Lang: EN.* 💲 Freemium: company profile and filing list free; director details from €3 (Standard Report), credit report €9

## Maps
(Cadastral Maps if available, GIS etc.)
- [landdirect.ie (Tailte Éireann – Land Registry)](https://www.landdirect.ie/) — digital Land Register: search the registry map and view folios online free; plain folio copy €5 by folio number; certified copies and full services need a Business Account (€125 minimum pre-payment). *Lang: EN.* 🏛️
- [Residential Property Price Register](https://www.propertypriceregister.ie/) — PSRA register of residential property sales since 1 January 2010 (date, price, address) compiled from stamp duty returns; online search and full download (PPR-ALL.zip). *Lang: EN.* 🏛️
- [GeoHive](https://www.geohive.ie/) — Tailte Éireann national geospatial data hub: map viewer, data catalogue and thematic apps with official land, environmental and other public-sector spatial data; some initiatives being decommissioned or migrated in 2026. *Lang: EN.* 🏛️
- [Historic Environment Viewer](https://heritagedata.maps.arcgis.com/apps/webappviewer/index.html?id=0c9eb9575b544081b0d296436d8f60f8) — map of National Monuments Service (archaeological sites and monuments) and National Inventory of Architectural Heritage records on Tailte Éireann basemaps; accept terms on launch. *Lang: EN.* 🏛️
- [Tailte Éireann Valuation Open Data API](https://www.tailte.ie/en/valuation/open-data/api/) — real-time valuation data for commercial (rateable) properties in 28 post-revaluation rating authority areas: address, category, use, floor areas, NAV, rateable valuation, Eircode, ITM coordinates; API explorer, CSV/JSON/GeoJSON output. *Lang: EN, GA.* 🏛️
- [Department of Housing, Local Government and Heritage – Open Data Hub](https://data-housinggovie.opendata.arcgis.com/) — the Department's ArcGIS open data hub, including spatial data of the National Planning Application Database (NPAD). *Lang: EN.* 🏛️

## Vehicles

### Land
- [Check My Vehicle (vehicleservices.gov.ie)](https://www.vehicleservices.gov.ie/cmv) — government lookup by Irish registration number: motor tax status and expiry, tax class and basis of assessment, NCT/CVRT status, off-road declaration; no account needed. *Lang: EN.* 🏛️
- [NCTS – Check When NCT Due](https://www.ncts.ie/check-nct-due-date/) — National Car Testing Service: enter a registration number to see when the vehicle's NCT is due. *Lang: EN.* 🏛️
- [CVRT – CRW Expiry Date Reminder](https://operator.cvrt.ie/Vehicle/CRWExpiryTestReminder) — Road Safety Authority commercial vehicle testing portal: enter a registration number (captcha) to confirm make, model, colour and year and set a Certificate of Roadworthiness expiry reminder. *Lang: EN.* 🏛️
- [MotorCheck](https://www.motorcheck.ie/) — Irish vehicle history checks; free registration check returns make, model, version, body type, fuel, transmission, current colour, UK import alert and number of records held. *Lang: EN.* 💲 Freemium: basic identity check free; finance, mileage, write-off and tax history in paid reports

### Maritime
- [European Community Fleet Register – Irish fishing fleet (Department of Agriculture, Food and the Marine)](https://www.gov.ie/en/department-of-agriculture-food-and-the-marine/publications/european-community-fleet-register) — publication with a report of all currently registered Irish sea-fishing vessels, plus a link to the EU fleet register database. *Lang: EN, GA.* 🏛️
- [MarineTraffic](https://www.marinetraffic.com/) — global AIS vessel tracking; covers Irish ports and coastal waters. *Lang: EN.* 💲 Freemium: live map free; historical data and advanced features paid

### Aviation
- [Irish Aviation Authority – Current Aircraft Register and Monthly Changes](https://www.iaa.ie/general-aviation/aircraft-registration-leasing/current-aircraft-register-and-monthly-changes) — monthly .xlsx files of all aircraft on the Irish civil register and monthly change files (March 2024 – September 2025); since October 2025 the live register is on MySRS (sign-in). *Lang: EN.* 🏛️
- [Dublin Airport – Flight information](https://www.dublinairport.com/flight-information) — live departures and arrivals at Ireland's main airport, filter by date and terminal. *Lang: EN.*
- [Flightradar24](https://www.flightradar24.com/) — global ADS-B flight tracker covering Irish airspace and airports. *Lang: EN.* 💲 Freemium: live map free; alerts and extended features by subscription (7-day trial)

## People
(Names, Addresses, Yellow Pages, White Pages etc.)
- [Register of Members' Interests (Houses of the Oireachtas)](https://www.oireachtas.ie/en/members/register-of-members-interests/) — annual registers of interests of TDs and Senators under the Ethics in Public Office Acts: occupations, shares, directorships, land, gifts, property, travel, remunerated positions, contracts; PDF, latest Dáil register covers 2025. *Lang: EN, GA.* 🏛️
- [Lobbying.ie – Register of Lobbying](https://www.lobbying.ie/app/home/search) — search the register of returns of lobbying activity and the directory of registered lobbyists; list of designated public officials. *Lang: EN.* 🏛️
- [Census of Ireland 1901 & 1911 (National Archives of Ireland)](https://nationalarchives.ie/collections/search-the-census/) — household returns searchable by surname, first name, county, townland/street, DED, age and sex, with advanced fields (occupation, religion, birthplace, marital status, etc.). *Lang: EN.* 🏛️
- [Census of Ireland 1926 (National Archives of Ireland)](https://nationalarchives.ie/collections/search-the-1926-census/) — 1926 census returns for the 26 counties, released in 2026; search by surname, first name, county, townland/street and DED, with a results map. *Lang: EN.* 🏛️
- [Eircode Finder](https://finder.eircode.ie/#/) — official postcode lookup: find the Eircode of any address in the State by address search or on a map, or check an Eircode. *Lang: EN.* 🏛️
- Try [OSINT Industries](https://app.osint.industries) and don't forget about the [Digital Profiler's Toolkit](https://github.com/paulpogoda/Digital-Profiler-s-Toolkit)

## Public procurement
- [eTenders – Latest Notices](https://www.etenders.gov.ie/epps/prepareCurrentOpportunities.do?currentType=notice) — national eProcurement platform of the Office of Government Procurement: 20,000+ notices including contract award notices (below and above EU threshold) with contracting authority, title and publication date; advanced search of calls for tender; browsing without login. *Lang: EN.* 🏛️
- [Contract Notices Published on eTenders (OGP open data)](https://data.gov.ie/en_GB/dataset/contract-notices-published-on-etenders) — CSV of all competitions published on eTenders from 01/01/2013 to 30/06/2026: tender notices, contract awards, procedures and supplier information; CC BY 4.0. *Lang: EN.* 🏛️
- [Office of Government Procurement – open datasets](https://data.gov.ie/en_GB/organization/office-of-government-procurement) — OGP datasets on data.gov.ie, including quarterly "Contracts for Mini-Competitions and Standalone Awards" (2023, 2024 Q1–Q4). *Lang: EN.* 🏛️
- [TED – Tenders Electronic Daily](https://ted.europa.eu/) — online supplement to the Official Journal of the EU, where Irish above-threshold tender and award notices are published. *Lang: EN + other EU languages.* 🏛️
- [Mercell / EU-Supply CTM – legacy eTenders notices](https://irl.eu-supply.com/ctm/Company/CompanyInformation/Index/351) — former eTenders back end; historical notices (e.g. 2020–2021) and buyer profiles (here: Office of Government Procurement) remain viewable without login. *Lang: EN.*

## WHOIS
- [.ie WHOIS search (IE Domain Registry)](https://www.weare.ie/find-or-change-your-registrar/) — official .ie registry WHOIS: registration and renewal dates, registrar, registrar abuse contact, DNS; holder name shown only when the holder is a company; port-43 server whois.weare.ie. *Lang: EN.*
- [.ie RDAP service](https://rdap.weare.ie/) — RDAP endpoint of the .ie registry for structured domain lookups. *Lang: EN.*
- [.ie Accredited Registrar List](https://www.weare.ie/accredited-registrar-list/) — 48 accredited .ie registrars with links to their sites; identify and contact the registrar behind a .ie domain. *Lang: EN.*
- [.ie Dispute Resolution](https://www.weare.ie/dispute-resolution/) — .ie domain dispute policy (WIPO-administered) and procedure: criteria, transfer of the domain 21 days after an upheld decision. *Lang: EN.*
- [.ie Domain Statistics](https://www.weare.ie/domain-stats/) — registry statistics on .ie registrations, new registrations, deletions and web/DNS/mail infrastructure; links to .ie Domain Profile Report and Domain Snapshot. *Lang: EN.*
- [IANA Root Zone Database – .ie](https://www.iana.org/whois?q=ie) — IANA record for the .ie ccTLD: registry operator (IE Domain Registry CLG), WHOIS server, contacts. *Lang: EN.*

---

## Contributing

To contribute to this repository:
1. Verify all links are working and accessible
2. Provide accurate descriptions of database contents
3. Follow the 7-category structure
4. Include official government sources when available
5. Submit pull requests with detailed change descriptions

## Legal Disclaimer

This repository is for educational and legitimate investigative purposes only. Users are responsible for:
- Complying with all applicable laws and regulations
- Respecting terms of service for all databases and tools
- Using information ethically and responsibly
- Obtaining proper authorization when required

The information provided is for informational purposes only and should not be considered legal advice.

---

**Repository maintained by the [OSINT-for-Countries-V2.0 community](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)**
