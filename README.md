# Media Framing of the Tigray Conflict: A Comparative Analysis of Domestic and Western News Coverage

## Project Aim

This project investigates how the Tigray conflict (2020–2022) was framed by domestic Ethiopian media and major Western outlets.  
We focus on two Ethiopian state-affiliated newspapers—**Addis Zemen** and **The Ethiopian Herald**—and two leading Western news organizations—**The New York Times** and **The Washington Post**.

Through comparative content analysis, we aim to highlight differences and similarities in conflict reporting, narrative construction, and source framing between domestic and international media.

## Project Outcome

- 📚 A portion of this research will contribute to a forthcoming book chapter in the edited volume:  
  **“Digital Battlefields: Transforming Media Narratives in Contemporary War and Conflict”**, to be published by **Palgrave Macmillan**.
- 🔬 The broader research will continue beyond the book chapter, aiming to produce extended analyses and multiple scholarly publications.

## Acknowledgments

This repository was created to promote research transparency and accessibility.  
The datasets are intended for academic research and educational purposes.  
If you utilize any portion of the resources provided here, please acknowledge appropriately.


## Researchers

- **Endalkachew H. Chala**, Principal Researcher
- **Tewodros Workneh, Ph.D.**, Principal Researcher

## License

This work is made available for **non-commercial, academic purposes only**.

---

## Repository Structure

```bash
tigray-war-news-framing-comparison/
├── data/
│   ├── domestic/
│   │   ├── addis_zemen_links.csv
│   │   ├── ethiopian_herald_links.csv
│   ├── international/
│   │   ├── nyt_links.csv (coming soon)
│   │   ├── washington_post_links.csv (coming soon)
├── scripts/
│   ├── scrape_ethiopian_herald.py
│   ├── scrape_addis_zemen.py (future)
├── README.md

---

## Data Collection Methods

### Domestic Media (Addis Zemen and The Ethiopian Herald)

- Article links were collected through a combination of manual curation and Python-based scraping.
- Tools and libraries used:
  - `requests`
  - `BeautifulSoup`
  - `Selenium`
  - `webdriver_manager`
- Both full PDFs and preview images of front pages were archived where available.

### Western Media (The New York Times and The Washington Post)

- Collection is in progress.
- Data will be gathered using public APIs, official archives, and manual retrieval where necessary.

---
