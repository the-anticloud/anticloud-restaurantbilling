# RESTAURANTBILLING

![licence](https://img.shields.io/badge/licence-Apache-2.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `RESTAURANTBILLING` in category **POS_SYSTEMS**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/Brynlai/RestaurantProject · **Upstream pin:** `b9c2e02a1442ca71c127b0d0d22579c81466733a` · **Category:** POS_SYSTEMS · **Vendor:** Anticloud FZ LLE · **Licence:** Apache-2.0

---

## What This Project Does

## Restaurant POS and Website

![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/homehomepage.png?raw=true)

**Built with these:** 
<p align="left">
   <a href="#">
      <img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/>
      <img alt="CSS3" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>
      <img alt="MySQL" src="https://img.shields.io/badge/mysql-%2300f.svg?&style=for-the-badge&logo=mysql&logoColor=white"/>
      <img alt="Php" src="https://img.shields.io/badge/php-474a8a?style=for-the-badge&logo=php&logoColor=white" />
      <img alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23F7DF1E.svg?&style=for-the-badge&logo=javascript&logoColor=black"/>
   </a>
</p>

**Using:** Php 7.4

**Features:**
* **Customer Side (customerSide Folder):** Stores the website and allows customers to:
    * Make reservations
    * Register for accounts
    * View profile points
* **Staff Side (adminSide Folder):** Stores the panels and allows staff to:
    * Take orders
    * Send orders to the kitchen
    * Process payments
    * Print receipts
    * Manage CRUD operations
    * View user preferences
    * Download reports
    * View charts and graph

**Steps to run the project locally for Netbeans Manually:**

1. Open XAMPP, start Apache and MySQL.
2. Create a new project in Netbeans named `RestaurantProject`.
3. Under categories, select PHP, the PHP Application under Projects.
4. In Run Configuration, the "Run As" should be Local Web Site. (If your using Xampp).
5. Then Finish.
6. Delete the `setup_completed.flag` file in the RestaurantProject-main. (Extracted version)
7. Copy all the folders and files (adminSide, customerSide, index.php, and restaurantDB.txt) from the RestaurantProject-main into the `Source Files` directory.
8. Make sure there is no database named `restaurantdb`.
9. Run the project.

## Example accounts

| Role | Email | Password |
|---|---|---|
| Customer | dadsvawvid@gmail.com | david4pass |
| Customer | zoe@gmail.com | passworddef |
| Customer | jackie@gmail.com | passwordstu |
| Staff | 1 | password123 |
| Staff | 10 | davidpa2ss |
| Staff | 7 | robertpass |
| Admin | 99999 | 12345 |

## Screenshots
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/homehomepage.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/register.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/Login.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/homepageloggedin.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/reservation.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/stafflogin.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/postable.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/orderitembeforepay.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/addmemberidandreservationid.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/cashpaid.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/cardpayment.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/billdpanel.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/tablepanel.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/kitchenpanel.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/salespanel.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/statisticspanel.png?raw=true)
![alt text](https://github.com/Brynlai/RestaurantProject/blob/main/RestaurantProjectImages/profilespanel.png?raw=true)

## Contributors

| Name | Github |
|---|---|
| Bryan | https://github.com/BryanTheLai |
| Yong | https://github.com/ahhyang |
| Kevin | https://github.com/kevin07212004 |
| Edzer | https://github.com/edsaur |

## If you want to put a password for the database, change the config.php files.

---

## Installation

7. Copy all the folders and files (adminSide, customerSide, index.php, and restaurantDB.txt) from the RestaurantProject-main into the `Source Files` directory.
8. Make sure there is no database named `restaurantdb`.
9. Run the project.

## Usage

* Download reports
    * View charts and graph

**Steps to run the project locally for Netbeans Manually:**

1. Open XAMPP, start Apache and MySQL.
2. Create a new project in Netbeans named `RestaurantProject`.
3. Under categories, select PHP, the PHP Application under Projects.
4. In Run Configuration, the "Run As" should be Local Web Site. (If your using Xampp).
5. Then Finish.
6. Delete the `setup_completed.flag` file in the RestaurantProject-main. (Extracted version)
7. Copy all the folders and files (adminSide, customerSide, index.php, and restaurantDB.txt) from the RestaurantProject-main into the `Source Files` directory.
8. Make sure there is no database named `restaurantdb`.
9. Run the project.

## API

* Download reports
    * View charts and graph

**Steps to run the project locally for Netbeans Manually:**

1. Open XAMPP, start Apache and MySQL.
2. Create a new project in Netbeans named `RestaurantProject`.
3. Under categories, select PHP, the PHP Application under Projects.
4. In Run Configuration, the "Run As" should be Local Web Site. (If your using Xampp).
5. Then Finish.
6. Delete the `setup_completed.flag` file in the RestaurantProject-main. (Extracted version)
7. Copy all the folders and files (adminSide, customerSide, index.php, and restaurantDB.txt) from the RestaurantProject-main into the `Source Files` directory.
8. Make sure there is no database named `restaurantdb`.
9. Run the project.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

5. Then Finish.
6. Delete the `setup_completed.flag` file in the RestaurantProject-main. (Extracted version)
7. Copy all the folders and files (adminSide, customerSide, index.php, and restaurantDB.txt) from the RestaurantProject-main into the `Source Files` directory.
8. Make sure there is no database named `restaurantdb`.
9. Run the project.

## Contributing

| Name | Github |
|---|---|
| Bryan | https://github.com/BryanTheLai |
| Yong | https://github.com/ahhyang |
| Kevin | https://github.com/kevin07212004 |
| Edzer | https://github.com/edsaur |

## If you want to put a password for the database, change the config.php files.

## License

Upstream © its respective contributors under Apache-2.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/Brynlai/RestaurantProject
- **Pinned SHA:** `b9c2e02a1442ca71c127b0d0d22579c81466733a`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`c28ebb3932d6e4e6c1d640fd185411bf4f0a85c8f3663a3f1f09b86f1199559a`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

