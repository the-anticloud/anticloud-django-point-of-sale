# DJANGO POINT OF SALE

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-supermarkets-lightgrey)

> Anticloud-hardened packaging of the upstream project `DJANGO_POINT_OF_SALE` in category **SUPERMARKETS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SUPERMARKETS · **Upstream:** https://github.com/betofleitass/django_point_of_sale · **Upstream pin:** `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

## Django Point of Sale (POS) 💸

A Point of Sale web app for businesses built with Python and Django for learning purposes.

<a><img src="https://user-images.githubusercontent.com/95726794/212497770-a3e241e7-0c77-4573-9d22-8f0ae813e958.png" width="70%" heigth="70%"></a>
<br></br>
<a><img src="https://user-images.githubusercontent.com/95726794/212497784-80a48617-759c-4415-aa1c-4591b9892c3d.png" width="70%" heigth="70%"></a>

## Table of Contents:
- [Features](#features)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Run it locally](#run-it-locally)
- [Contributing](#contributing)
- [License](#license)

## Screenshots
[Click Here](screenshots/README.md)

## Features
- Login Page with User authentication
- Dashboard Page with statistics and graphs
- DataTables with print, copy, to CSV, and to PDF buttons
- Categories and Products Management
- Clients Management
- Sales Management

## Tech Stack

- Frontend: HTML, CSS, JavaScript, Boostrap, SweetAlert, DataTables
- Backend: Django, Python, Ajax, SQLite 

## Installation

### Prerequisites
- [Python 3.x](https://www.python.org/downloads/)
- [pip package manager](https://pip.pypa.io/en/stable/installation/)
- [git](https://git-scm.com/downloads)
  
#### Browser Compatibility Notice: Firefox NOT Supported ‼
#### Please Use Chrome or Edge Browsers ‼
    
  1. source or download the project:

  ` git source https://github.com/betofleitass/django_point_of_sale`

  2. Go to the project directory

  ` cd django_point_of_sale`

  3. Create a virtual environment :

  PowerShell:
  ```
   python -m venv venv
   venv\Scripts\Activate.ps1
  ```
  
  Linux:
  ```
  python3 -m venv venv
  source venv/bin/activate
  ```

  4. Install dependencies:  
  ` pip install -r requirements.txt`
  
  5.  Update pip and setuptools  
  ` python -m pip install --upgrade pip setuptools`  
  
  6. Install GTK to create the PDF files:  
   [Official documentation](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#installation)
  
  7. Windows Users (IMPORTANT)‼:

     Only Windows 11 64-bit is supported ‼

     After installing GTK, you need to add it to your system's Path environment variable. Follow these steps:

      - Assuming you installed GTK at:
        `C:\Program Files\GTK3-Runtime Win64\bin`  
        This will be your new variable that you need to add to Path
        
      - Refer to this tutorial for detailed instructions on adding to the Path environment variable:
        [Tutorial add to the Path enviroment variable](https://helpdeskgeek.com/windows-10/add-windows-path-environment-variable/)  
    
      - If you encounter an error such as "cannot load library," refer to this documentation for troubleshooting:
        [Missing Library Error](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#missing-library)  
  
  9. Restart your computer: After completing the steps above, it is essential to restart your computer for the changes to take effect properly. ‼
  
## Run it locally
After restarting your computer

1. Go to the project directory: `cd django_point_of_sale`

2. Activate the virtual enviroment

    PowerShell:
    ```
     venv\Scripts\Activate.ps1
    ```
    
    Linux:
    ```
    source venv/bin/activate
    ```
3. Go to the django_pos folder: `cd django_pos`

4. Make database migrations:  
  `python manage.py makemigrations` and 
  `python manage.py migrate`

5. Create superuser `python manage.py createsuperuser` 
  
   with the following data, or with the data you prefer:
   `username: admin,
    password: admin,
    email: admin@admin`

7. Run the server: `python manage.py runserver`

8. Open a browser and go to: `http://127.0.0.1:8000/`

9. Log In with your superuser credentials.
    

## Contributing

Contributions are always welcome!

- Fork this project;

- Create a branch with your feature: `git checkout -b my-feature`;

- Commit your changes: `git commit -m "feat: my new feature"`;

- Push to your branch: `git push origin my-feature`.

## Authors

- [@betofleitass](https://www.github.com/betofleitass)

##  License

This project is under [MIT License.](https://choosealicense.com/licenses/mit/)

[Back to top ⬆️](#django-point-of-sale-pos-)

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python (requirements)** (manifests: requirements.txt; scanned in UPSTREAM_CLONE)
- Top-level source layout: `django_pos/`, `screenshots/`
- Snapshot size: **1747 files**, **79668 lines of code** (measured; see Benchmarks)
- Primary languages: `.svg` (1074), `.js` (167), `.scss` (130), `.css` (75), `.py` (55), `.map` (48)
- Upstream commit pinned for this packaging: `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe`

---

## Installation

- [Run it locally](#run-it-locally)
- [Contributing](#contributing)
- [License](#license)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

1. source or download the project:

  ` git source https://github.com/betofleitass/django_point_of_sale`

  2. Go to the project directory

  ` cd django_point_of_sale`

  3. Create a virtual environment :

  PowerShell:
  ```
   python -m venv venv
   venv\Scripts\Activate.ps1
  ```
  
  Linux:
  ```
  python3 -m venv venv
  source venv/bin/activate
  ```

  4. Install dependencies:  
  ` pip install -r requirements.txt`
  
  5.  Update pip and setuptools  
  ` python -m pip install --upgrade pip setuptools`  
  
  6. Install GTK to create the PDF files:  
   [Official documentation](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#installation)
  
  7. Windows Users (IMPORTANT)‼:

     Only Windows 11 64-bit is supported ‼

     After installing GTK, you need to add it to your system's Path environment variable. Follow these steps:

      - Assuming you installed GTK at:
        `C:\Program Files\GTK3-Runtime Win64\bin`  
        This will be your new variable that you need to add to Path
        
      - Refer to this tutorial for detailed instructions on adding to the Path environment variable:
        [Tutorial add to the Path enviroment variable](https://helpdeskgeek.com/windows-10/add-windows-path-environment-variable/)  
    
      - If you encounter an error such as "cannot load library," refer to this documentation for troubleshooting:
        [Missing Library Error](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#missing-library)  
  
  9. Restart your computer: After completing the steps above, it is essential to restart your computer for the changes to take effect properly. ‼

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `DJANGO_POINT_OF_SALE` source tree vendored in `UPSTREAM_CLONE/` (Python (requirements) ecosystem). Public entry points:

- Source modules: `django_pos/`, `screenshots/`
- The snapshot declares 38 dependency references across 1 ecosystem(s); see Dependencies below.
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python (requirements) |
| Manifests detected | requirements.txt |
| Files in snapshot | 1747 |
| Lines of code | 79668 |
| Dependency references | 38 |
| Dependencies by ecosystem | npm: 38 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | grunt | ^1.1.0 | django_pos/static/assets/bootstrap-touchspin-master/package.json |
| npm | grunt-cli | ^1.3.2 | django_pos/static/assets/bootstrap-touchspin-master/package.json |
| npm | grunt-contrib-jshint | ^2.1.0 | django_pos/static/assets/bootstrap-touchspin-master/package.json |
| npm | grunt-contrib-concat | ^1.0.1 | django_pos/static/assets/bootstrap-touchspin-master/package.json |
| npm | grunt-contrib-uglify | ^4.0.1 | django_pos/static/assets/bootstrap-touchspin-master/package.json |
| npm | grunt-contrib-cssmin | ^3.0.0 | django_pos/static/assets/bootstrap-touchspin-master/package.json |
| npm | almond | ~0.3.1 | django_pos/static/assets/select2/package.json |
| npm | grunt | ^1.0.4 | django_pos/static/assets/select2/package.json |
| npm | grunt-cli | ^1.3.2 | django_pos/static/assets/select2/package.json |
| npm | grunt-contrib-concat | ^1.0.1 | django_pos/static/assets/select2/package.json |
| npm | grunt-contrib-connect | ^2.0.0 | django_pos/static/assets/select2/package.json |
| npm | grunt-contrib-jshint | ^1.1.0 | django_pos/static/assets/select2/package.json |
| npm | grunt-contrib-qunit | ^1.3.0 | django_pos/static/assets/select2/package.json |
| npm | grunt-contrib-requirejs | ^1.0.0 | django_pos/static/assets/select2/package.json |
| npm | grunt-contrib-uglify | ~4.0.1 | django_pos/static/assets/select2/package.json |
| ... | (23 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

PowerShell:
  ```
   python -m venv venv
   venv\Scripts\Activate.ps1
  ```
  
  Linux:
  ```
  python3 -m venv venv
  source venv/bin/activate
  ```

  4. Install dependencies:  
  ` pip install -r requirements.txt`
  
  5.  Update pip and setuptools  
  ` python -m pip install --upgrade pip setuptools`  
  
  6. Install GTK to create the PDF files:  
   [Official documentation](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#installation)
  
  7. Windows Users (IMPORTANT)‼:

     Only Windows 11 64-bit is supported ‼

     After installing GTK, you need to add it to your system's Path environment variable. Follow these steps:

      - Assuming you installed GTK at:
        `C:\Program Files\GTK3-Runtime Win64\bin`  
        This will be your new variable that you need to add to Path
        
      - Refer to this tutorial for detailed instructions on adding to the Path environment variable:
        [Tutorial add to the Path enviroment variable](https://helpdeskgeek.com/windows-10/add-windows-path-environment-variable/)  
    
      - If you encounter an error such as "cannot load library," refer to this documentation for troubleshooting:
        [Missing Library Error](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#missing-library)  
  
  9. Restart your computer: After completing the steps above, it is essential to restart your computer for the changes to take effect properly. ‼

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `DJANGO_POINT_OF_SALE` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2023 Alberto Fleitas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `DJANGO_POINT_OF_SALE` (category: SUPERMARKETS)
- **Upstream URL:** https://github.com/betofleitass/django_point_of_sale
- **Pinned commit (SHA):** `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`30033d2b3d71ba694dabff77106b6b82c5157ed0cd346b59237f31c6e2a1470a`.

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

