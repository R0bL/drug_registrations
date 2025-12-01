# Major Pharma Markets: Drug Registration Repositories and Clinical Trial Registries

**Research Date:** 2025-12-01

---

## Table 1: Drug Registration / Approved Medicines Repositories

| country_or_region | regulatory_authority_name | regulatory_authority_acronym | repository_name | repository_url | language | coverage_description | search_capabilities | export_or_api | notes | last_verified_date |
|-------------------|---------------------------|------------------------------|-----------------|----------------|----------|----------------------|---------------------|---------------|-------|-------------------|
| United States | Food and Drug Administration | FDA | Drugs@FDA | https://www.accessdata.fda.gov/scripts/cder/daf/ | English | Human prescription and OTC drugs approved since 1939 | Brand name, active ingredient, application number | Yes - openFDA API (https://open.fda.gov/apis/drug/) | Modern searchable database with REST API; JSON downloads available | 2025-12-01 |
| United States | Food and Drug Administration | FDA | Orange Book (Electronic) | https://www.fda.gov/drugs/drug-approvals-and-databases/approved-drug-products-therapeutic-equivalence-evaluations-orange-book | English | Approved drug products with therapeutic equivalence evaluations | Active ingredient, brand name, applicant | Yes - Data files (https://www.fda.gov/drugs/drug-approvals-and-databases/orange-book-data-files) | ZIP/text files updated monthly; also via NBER in SAS/Stata/CSV | 2025-12-01 |
| United States | Food and Drug Administration | FDA | Purple Book | https://purplebooksearch.fda.gov/ | English | FDA-licensed biological products including biosimilars | Product name, BLA number, licensee | Yes - Download available | Separate from Drugs@FDA; covers biologics | 2025-12-01 |
| European Union | European Commission / European Medicines Agency | EC/EMA | Union Register of Medicinal Products | https://ec.europa.eu/health/documents/community-register/html/reg_hum_act.htm | English (+ EU languages) | Centrally authorized human medicines in EU | Product name, active substance, ATC code, MA holder | Yes - EMA data downloads (https://www.ema.europa.eu/en/medicines/download-medicine-data) | JSON data files updated twice daily; ePI API available | 2025-12-01 |
| Germany | Federal Institute for Drugs and Medical Devices | BfArM | PharmNet.Bund | https://www.pharmnet-bund.de/PharmNet/EN/Public/Drug-information-system/_node.html | German, English | All authorized medicines in Germany (national + centralized) | Product name, active ingredient, PZN, company | Limited - SPCs and PILs downloadable | Free access since Feb 2025; cooperative project of BfArM, PEI, BVL, RKI | 2025-12-01 |
| France | National Agency for the Safety of Medicines and Health Products | ANSM | Base de Donnees Publique des Medicaments | https://base-donnees-publique.medicaments.gouv.fr/ | French | Medicines marketed or stopped <3 years in France | Medicine name, active substance, pathology | Yes - Open data on data.gouv.fr | Reference database; includes HAS, CNAMTS, CEPS data | 2025-12-01 |
| Spain | Spanish Agency of Medicines and Medical Devices | AEMPS | CIMA (Centro de Informacion de Medicamentos) | https://cima.aemps.es/ | Spanish | All authorized medicines in Spain | Product name, active ingredient, laboratory, ATC, barcode | Limited - No public API; mobile app with barcode scanning | Advanced search available; includes MeQA natural language search | 2025-12-01 |
| Italy | Italian Medicines Agency | AIFA | Banca Dati Farmaci | https://www.aifa.gov.it/en/dati-aifa | Italian, English | Human medicines authorized in Italy | Commercial name, active ingredient, company | Yes - Open data CC-BY 4.0 license | Renewed July 2024; mobile app available; includes doping info | 2025-12-01 |
| Netherlands | Medicines Evaluation Board | CBG-MEB | Geneesmiddeleninformatiebank | https://www.geneesmiddeleninformatiebank.nl/ | Dutch, English | All registered and homeopathic medicines in Netherlands | Product name, active substance, RVG number | Yes - Data file available | Updated weekly; includes SPCs, PARs, PILs | 2025-12-01 |
| United Kingdom | Medicines and Healthcare products Regulatory Agency | MHRA | MHRA Products | https://products.mhra.gov.uk/ | English | Licensed medicines in UK (human and veterinary) | Product name, PL number, active substance, A-Z list | No public API | Includes PILs, SPCs, PARs; Windsor Framework updates 2024-25 | 2025-12-01 |
| Japan | Pharmaceuticals and Medical Devices Agency | PMDA | PMDA Approved Products Database | https://www.pmda.go.jp/english/review-services/reviews/approved-information/drugs/0002.html | Japanese, English | Drugs, devices, regenerative products approved in Japan | Product name, approval date, company | Limited - PDF lists available | English submissions accepted from Sept 2024 for sponsors without Japanese affiliate | 2025-12-01 |
| China | National Medical Products Administration | NMPA | NMPA Drug Database | https://english.nmpa.gov.cn/database.html | Chinese, English (limited) | Approved drugs in China | Product name, approval number | No public API | English portal limited; main database in Chinese only; 84 new products approved in 2024 | 2025-12-01 |
| India | Central Drugs Standard Control Organisation | CDSCO | SUGAM Portal / Drugs@CDSCO | https://cdscoonline.gov.in/CDSCO/Drugs | English | Approved drugs in India | Drug name, approval type | Limited - PDF approval lists | SUGAM portal for applications; approval lists published as PDFs | 2025-12-01 |
| Canada | Health Canada | HC | Drug Product Database (DPD) | https://health-products.canada.ca/dpd-bdpp/ | English, French | ~15,000 marketed health products in Canada | DIN, brand name, company, active ingredient | Yes - REST API (https://health-products.canada.ca/api/documentation/dpd-documentation-en.html) | Excellent API; Open data portal; includes approved but not marketed since April 2024 | 2025-12-01 |
| Australia | Therapeutic Goods Administration | TGA | Australian Register of Therapeutic Goods (ARTG) | https://www.tga.gov.au/products/australian-register-therapeutic-goods-artg | English | All therapeutic goods legally supplied in Australia | Product name, ARTG number, sponsor, active ingredient | Limited - CSV/Excel export via visualization tool | ARTG visualization tool for advanced search; no public API; 4 exports needed for full data | 2025-12-01 |
| Brazil | National Health Surveillance Agency | ANVISA | ANVISA Drug Registry | https://www.gov.br/anvisa/pt-br/english/regulation-of-products/drugs | Portuguese, English (limited) | Registered medicines in Brazil | Product name, registration number | No public API | Electronic submissions mandatory; 15-18 month approval times; local partner required | 2025-12-01 |
| South Korea | Ministry of Food and Drug Safety | MFDS | MFDS Drug Products Database | https://www.mfds.go.kr/eng/brd/m_19/list.do | Korean, English | Approved drug products in Korea | Product name, approval date | Limited | 2024 Drug Approval Report published; 5-year license renewal required | 2025-12-01 |
| Switzerland | Swiss Agency for Therapeutic Products | Swissmedic | Swiss Medicinal Product Information (AIPS) | https://www.swissmedicinfo.ch/ | German, French, Italian, English | Authorized human medicines in Switzerland | Product name, active substance | Limited - Lists downloadable | Updated daily; 46 new active substances approved in 2024 (+12% YoY) | 2025-12-01 |
| Singapore | Health Sciences Authority | HSA | HSA PRISM / Therapeutic Products Register | https://eservice.hsa.gov.sg/prism/common/enquirepublic/SearchDRBProduct.do | English | Registered therapeutic products in Singapore | Product name, license number, active ingredient | Yes - Dataset on data.gov.sg | Infosearch available; Swissmedic added as reference agency in 2024 | 2025-12-01 |

---

## Table 2: Clinical Trial Registries

| country_or_region | registry_name | registry_operator | registry_type | registry_url | language | scope_coverage_description | approx_registered_trials_count | trial_count_as_of_date | count_estimation_method | api_or_bulk_export | notes |
|-------------------|---------------|-------------------|---------------|--------------|----------|---------------------------|-------------------------------|----------------------|------------------------|-------------------|-------|
| United States (global scope) | ClinicalTrials.gov | NIH/NLM | Global | https://clinicaltrials.gov/ | English | All interventional and observational studies worldwide; ~75% interventional | ~500,000 | 2024-12 | NLM milestone announcement (500K in 2024) | Yes - REST API v2.0 (https://clinicaltrials.gov/data-api/api); bulk JSON download | World's largest registry; 25th anniversary in 2024; classic API retired June 2024 |
| European Union | EU Clinical Trials Information System (CTIS) | EMA | Regional | https://euclinicaltrials.eu/ | EU languages | Clinical trials under EU CTR (from Jan 2022) | ~6,700 | 2024-10-20 | CTIS public portal | Limited - transparency rules revised June 2024 | Mandatory for new trials from Jan 2023; all trials transitioned by Jan 2025 |
| European Union (legacy) | EU Clinical Trials Register (EudraCT) | EMA | Regional | https://www.clinicaltrialsregister.eu/ | EU languages | Legacy trials under Directive 2001/20/EC (2004-2025) | ~44,400 | 2024-10 | Registry homepage | Limited | No new registrations since Feb 2023; legacy data maintained |
| United Kingdom | ISRCTN Registry | BMC/Springer Nature | Global (UK-primary) | https://www.isrctn.com/ | English | All clinical research studies; interventional and observational | ~25,500 | 2025-03 | Registry announcement | Yes - API available | 25th anniversary in 2025; UK CTIMPs auto-registered via HRA/IRAS |
| Japan | Japan Registry of Clinical Trials (jRCT) | MHLW | National | https://jrct.mhlw.go.jp/en-top | Japanese, English | Specified clinical trials under Clinical Trials Act 2018 | ~5,000+ | 2024 (est.) | Historical growth extrapolation | Limited | WHO Primary Registry; part of Japan Primary Registries Network (JPRN) |
| Japan | UMIN-CTR | University Hospital Medical Information Network | National | https://www.umin.ac.jp/ctr/ | Japanese, English | Clinical trials in Japan (voluntary registration) | ~50,000+ | 2024 (est.) | Historical data (~5,000/year registrations) | Limited | Larger than jRCT; academic/hospital trials |
| China | Chinese Clinical Trial Registry (ChiCTR) | West China Hospital | National | https://www.chictr.org.cn/ | Chinese, English | Clinical trials in China; excludes traditional medicine since July 2024 | ~70,000+ | 2024 (est.) | April 2023 count: 68,713 + growth | Limited | 3rd largest globally; traditional medicine moved to ITMCTR from July 2024 |
| India | Clinical Trials Registry - India (CTRI) | ICMR/NIMS | National | https://ctri.nic.in/ | English | Clinical trials in India; mandatory since 2009 | ~25,000+ | 2024 (est.) | Based on ~20,160 in decadal study + growth | Limited | WHO Primary Registry; prospective registration mandatory since April 2018 |
| Canada | Health Canada Clinical Trials Database | Health Canada | National | https://health-products.canada.ca/ctdb-bdec/ | English, French | Phase I-III trials authorized by Health Canada (from April 2013) | ~3,200 ongoing | 2024-01 | IMC 2024 Research Report | Yes - Open data portal | ~900 new authorizations annually; ~500K subjects enrolled |
| Australia/New Zealand | ANZCTR | NHMRC Clinical Trials Centre | Regional | https://anzctr.org.au/ | English | All clinical trials in Australia/NZ and beyond | ~25,500 | 2025-03 | Registry homepage | Yes - API available | WHO Primary Registry since 2007; accepts international trials |
| Brazil | ReBEC (Registro Brasileiro de Ensaios Clinicos) | FIOCRUZ/PAHO/Ministry of Health | National | https://ensaiosclinicos.gov.br/ | Portuguese | Clinical trials in Brazil; phases I-IV mandatory | ~8,300 registered | 2024 (current) | Registry homepage | Limited | WHO Primary Registry since 2011; ~4,600 currently recruiting |
| South Korea | Clinical Research Information Service (CRIS) | KDCA/MOHW | National | https://cris.nih.go.kr/ | Korean, English | Clinical trials in Korea | ~5,000+ | 2024 (est.) | Based on 1,323 in 2014 + growth | Limited | WHO Primary Registry; 11th ICTRP member |
| Switzerland | Swiss National Clinical Trials Portal (SNCTP) | FOPH/swissethics | National | https://kofam.ch/en/snctp-portal | German, French, Italian, English | All clinical trials authorized by Swiss ethics committees since 2014 | ~14,000 (Swiss) + 95,000 (neighboring) | 2023-04 | Registry documentation | Limited | Mandatory registration; includes ICTRP cross-references |
| Singapore | HSA Clinical Trials Register | Health Sciences Authority | National | https://www.hsa.gov.sg/clinical-trials/clinical-trials-register | English | Active clinical trial sites in Singapore | Unknown | - | Not publicly displayed | No | Launched 2012; lists active sites only; status updates required every 6 months |
| Global | WHO ICTRP | World Health Organization | Global meta-registry | https://www.who.int/tools/clinical-trials-registry-platform | Multiple | Aggregates 20 primary registries worldwide | 700,000+ | 2024 (est.) | Based on 689,793 by end 2020 + growth | Yes - Search portal + data exports | Meta-search across all primary registries; includes 186K US, 136K China, 74K India trials (1999-2024) |

---

## Summary of Findings

### Drug Registration Repositories

#### Markets with Strong, Modern, Searchable Repositories:
1. **United States (FDA)** - Gold standard with openFDA REST API, multiple databases (Drugs@FDA, Orange Book, Purple Book), JSON downloads, and open data initiatives. Excellent for programmatic access.

2. **Canada (Health Canada)** - Excellent Drug Product Database with full REST API, open data portal, comprehensive coverage including approved-but-not-marketed products since April 2024.

3. **European Union (EMA/EC)** - Union Register with JSON data files updated twice daily, ePI API for electronic product information. Strong transparency and data availability.

4. **Singapore (HSA)** - Official dataset on data.gov.sg with API access, PRISM search system. Modern infrastructure.

5. **Netherlands (CBG-MEB)** - Geneesmiddeleninformatiebank with data file exports, weekly updates, comprehensive documentation.

#### Markets with Good Repositories but Limited Export/API:
- **United Kingdom (MHRA)** - MHRA Products searchable but no public API
- **Germany (BfArM)** - PharmNet.Bund comprehensive but limited programmatic access
- **France (ANSM)** - Open data available on data.gouv.fr
- **Italy (AIFA)** - Open data with CC-BY license, renewed in 2024
- **Spain (AEMPS)** - CIMA advanced search but no API
- **Japan (PMDA)** - English interface improving, PDF-based lists
- **Switzerland (Swissmedic)** - Daily updates, downloadable lists
- **Australia (TGA)** - ARTG visualization tool with CSV export (requires 4 separate exports)
- **South Korea (MFDS)** - English interface available, limited exports

#### Markets with Fragmented/Limited Access:
- **China (NMPA)** - English portal very limited; main database in Chinese only; no public API
- **India (CDSCO)** - SUGAM portal functional but approval lists primarily PDF-based
- **Brazil (ANVISA)** - Portuguese-primary; electronic submission required but limited public data access

---

### Clinical Trial Registries

#### Markets with Robust Registries, Clear Stats, and APIs:
1. **ClinicalTrials.gov (US/Global)** - ~500,000 studies, REST API v2.0, bulk JSON downloads, comprehensive search. The definitive global resource.

2. **ANZCTR (Australia/NZ)** - ~25,500 trials, API available, WHO Primary Registry, accepts international trials.

3. **ISRCTN (UK/Global)** - ~25,500 studies, API available, auto-registration for UK CTIMPs, 25 years operational.

4. **Health Canada CTD** - Good open data access, ~3,200 ongoing trials tracked, annual statistics published.

5. **WHO ICTRP** - Meta-search across 20 registries, 700K+ trials aggregated, excellent for comprehensive searches.

#### Markets with Good Registries but Limited Export:
- **EU CTIS** - New system (~6,700 trials), replacing EudraCT, transparency rules improving
- **EU EudraCT (legacy)** - ~44,400 trials, legacy data maintained but no new entries
- **ChiCTR (China)** - ~70,000+ trials, 3rd largest globally, limited English interface
- **CTRI (India)** - ~25,000+ trials, WHO Primary Registry, mandatory registration
- **ReBEC (Brazil)** - ~8,300 registered trials, WHO Primary Registry
- **SNCTP (Switzerland)** - ~14,000 Swiss trials, cross-references ICTRP data
- **jRCT/UMIN-CTR (Japan)** - Multiple registries; jRCT mandatory for specified trials, UMIN larger for voluntary

#### Markets with Limited/Incomplete Registry Data:
- **South Korea (CRIS)** - Trial counts not prominently displayed; estimated ~5,000+
- **Singapore (HSA CTR)** - Lists active sites only; total count not publicly available

---

### Key Observations

1. **API Availability**: FDA/openFDA and Health Canada lead in API access. EMA has made significant progress with JSON exports and ePI API. Most other markets lack true programmatic access.

2. **Language Barriers**: China and Brazil present significant challenges with limited English interfaces. Japan has improved with English submission acceptance since September 2024.

3. **Data Fragmentation**:
   - EU has both CTIS (new) and EudraCT (legacy) systems during transition
   - Japan has multiple registries (jRCT, UMIN-CTR, JAPIC, JMACCT)
   - Some markets require navigating multiple databases for complete coverage

4. **Trial Count Transparency**: ClinicalTrials.gov, ANZCTR, and EudraCT prominently display trial counts. Others require searching or estimation.

5. **Recent Improvements (2024)**:
   - ClinicalTrials.gov: API v2.0 launched, 500K milestone
   - Health Canada: Now includes approved-but-not-marketed products
   - EMA: Revised CTIS transparency rules (June 2024)
   - PMDA: English submission acceptance for foreign sponsors
   - PharmNet.Bund: Free access since February 2025

---

## Sources

### Drug Registration Repositories
- [FDA Drug Approvals and Databases](https://www.fda.gov/drugs/development-approval-process-drugs/drug-approvals-and-databases)
- [FDA Orange Book](https://www.fda.gov/drugs/drug-approvals-and-databases/approved-drug-products-therapeutic-equivalence-evaluations-orange-book)
- [openFDA API](https://open.fda.gov/apis/drug/)
- [EMA Medicines](https://www.ema.europa.eu/en/medicines)
- [EMA Download Medicine Data](https://www.ema.europa.eu/en/medicines/download-medicine-data)
- [Union Register of Medicinal Products](https://ec.europa.eu/health/documents/community-register/html/reg_hum_act.htm)
- [PharmNet.Bund](https://www.pharmnet-bund.de/PharmNet/EN/Home/_node.html)
- [Base de Donnees Publique des Medicaments (France)](https://base-donnees-publique.medicaments.gouv.fr/)
- [AEMPS CIMA](https://cima.aemps.es/)
- [AIFA Banca Dati Farmaci](https://www.aifa.gov.it/en/dati-aifa)
- [CBG-MEB Geneesmiddeleninformatiebank](https://www.geneesmiddeleninformatiebank.nl/)
- [MHRA Products](https://products.mhra.gov.uk/)
- [PMDA Approved Products](https://www.pmda.go.jp/english/review-services/reviews/approved-information/drugs/0002.html)
- [NMPA Database](https://english.nmpa.gov.cn/database.html)
- [CDSCO Approved Drugs](https://cdscoonline.gov.in/CDSCO/Drugs)
- [Health Canada Drug Product Database](https://www.canada.ca/en/health-canada/services/drugs-health-products/drug-products/drug-product-database.html)
- [Health Canada DPD API](https://health-products.canada.ca/api/documentation/dpd-documentation-en.html)
- [TGA ARTG](https://www.tga.gov.au/products/australian-register-therapeutic-goods-artg)
- [ANVISA Drug Products](https://www.gov.br/anvisa/pt-br/english/regulation-of-products/drugs)
- [MFDS Drug Products](https://www.mfds.go.kr/eng/brd/m_19/list.do)
- [Swissmedic](https://www.swissmedic.ch/swissmedic/en/home/services/medicinal-product-information.html)
- [HSA Therapeutic Products](https://www.hsa.gov.sg/therapeutic-products)
- [HSA data.gov.sg dataset](https://data.gov.sg/datasets/d_767279312753558cbf19d48344577084/view)

### Clinical Trial Registries
- [ClinicalTrials.gov](https://clinicaltrials.gov/)
- [ClinicalTrials.gov API](https://clinicaltrials.gov/data-api/api)
- [ClinicalTrials.gov Trends](https://clinicaltrials.gov/about-site/trends-charts)
- [NLM 500K Milestone Announcement](https://nlmdirector.nlm.nih.gov/2025/04/02/clinicaltrials-gov-a-25-year-journey-to-a-half-million-registered-studies/)
- [EU CTIS](https://euclinicaltrials.eu/)
- [EU Clinical Trials Register (EudraCT)](https://www.clinicaltrialsregister.eu/)
- [ISRCTN Registry](https://www.isrctn.com/)
- [jRCT](https://jrct.mhlw.go.jp/en-top)
- [NIPH Clinical Trials Search (Japan)](https://rctportal.niph.go.jp/en)
- [ChiCTR](https://www.chictr.org.cn/indexEN.html)
- [CTRI India](https://ctri.nic.in/)
- [Health Canada Clinical Trials Database](https://health-products.canada.ca/ctdb-bdec/)
- [ANZCTR](https://anzctr.org.au/)
- [ReBEC Brazil](https://ensaiosclinicos.gov.br/)
- [CRIS South Korea](https://cris.nih.go.kr/)
- [SNCTP Switzerland](https://kofam.ch/en/snctp-portal)
- [HSA Clinical Trials Register](https://www.hsa.gov.sg/clinical-trials/clinical-trials-register)
- [WHO ICTRP](https://www.who.int/tools/clinical-trials-registry-platform)
- [WHO ICTRP Statistics](https://www.who.int/observatories/global-observatory-on-health-research-and-development/monitoring/number-of-trial-registrations-by-year-location-disease-and-phase-of-development)
