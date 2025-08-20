# Companies-House---Easy-API-Extraction
Python tool for quick, reliable extraction of company and director data from the UK Companies House REST API.

This tool can be tailored to the client's specific requirements in no time at all. You can find me on Upwork https://www.upwork.com/freelancers/ericfisher?mp_source=share

Or contact me direct :)  efish707@gmail.com


# 🕊 Companies House – Easy API Extraction

A Python project that demonstrates how to extract structured company and director data from the **UK Companies House REST API**.  
This example shows how APIs can be used for smooth, reliable data extraction — perfect for data mining, enrichment, or Upwork portfolio projects.  

---

## 🔹 Features
- Search Companies House by keyword (e.g. **“venture capital”**).
- Retrieve company details (number, name, status, SIC codes, incorporation date).
- Extract officer/director information with role and appointment dates.
- Generate a Google **LinkedIn search URL** for each officer.
- Export results to **CSV** for easy use in Excel or analysis.

---

## 🔹 Example Output (CSV)

| company_number | company_name              | status  | sic_codes | incorporated_on | officer_name | officer_role | appointed_on | dob_month_year | linkedin_search_url |
|----------------|---------------------------|---------|-----------|-----------------|--------------|--------------|--------------|----------------|----------------------|
| 00445790       | TESCO PLC                 | active  | 47110     | 1947-11-27      | JOHN SMITH   | Director     | 2018-06-01   | 05/1975        | [Google Search](https://www.google.com/search?q=site%3Alinkedin.com%2Fin+%22JOHN+SMITH%22+%22TESCO+PLC%22) |
| 12345678       | VENTURE PARTNERS LIMITED | active  | 64304     | 2015-04-12      | JANE DOE     | Director     | 2015-04-12   | 11/1982        | [Google Search](https://www.google.com/search?q=site%3Alinkedin.com%2Fin+%22JANE+DOE%22+%22VENTURE+PARTNERS%22) |

---

## 🔹 Requirements
- Python 3.8+  
- `requests` library  

Install dependencies:  
```bash
pip install requests
