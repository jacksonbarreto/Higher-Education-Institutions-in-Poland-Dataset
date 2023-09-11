# Higher Education Institutions in Poland Dataset
This repository contains a dataset of higher education institutions in Poland. The dataset comprises 131 public higher education institutions and 216 private higher education institutions in Poland. The data was collected on 24/11/2022. 
This dataset was compiled in response to a cybersecurity investigation of Poland's higher education institutions' websites [1]. The data is being made publicly available to promote open science principles [2].

## Data

The data includes the following fields for each institution:

- Id: A unique identifier assigned to each institution.
- Region: The federal state in which the institution is located.
- Name: The original name of the institution in Polish.
- Name_EN: The international name of the institution in English.
- Category: Indicates whether the institution is public or private.
- Url: The website of the institution.

## Methodology

The dataset was compiled using data from two primary sources:

- Public Higher Education Institutions: Data was sourced from the official website of the Ministry of Education and Science of Poland [3].

- Private Higher Education Institutions: Data was obtained from the RAD-on system, which is part of the Integrated Information Network on Science and Higher Education [4].

For the international names in English, the following methodology was employed:

Both Polish and English names were retained for each institution. This decision was based on the fact that some universities do not have their English versions available in official sources.

English names were primarily sourced from:
- The Polish National Agency for Academic Exchange's official document [5].
- The website Studies in English [6].
- Official websites of the respective Higher Education Institutions.

In instances where English names were not readily available from the aforementioned sources, the GPT-3.5 model was employed to propose suitable names. These proposed names are distinctly marked in blue within the dataset file (hei_poland_en.xls).

## Usage

This data is available under the Creative Commons Zero (CC0) license and can be used for academic research purposes. We encourage the sharing of knowledge and the advancement of research in this field by adhering to open science principles [2].

If you use this data in your research, please cite the source and include a link to this repository. To properly attribute this data, please use the following DOI:
**10.5281/zenodo.8333573

## Contribution

If you have any updates or corrections to the data, please feel free to open a pull request or contact us directly. Let's work together to keep this data accurate and up-to-date.

## Acknowledgment

We would like to express our gratitude to the Ministry of Education and Science of Poland and the RAD-on system for providing the information used in this dataset.

We would like to acknowledge the support of the Norte Portugal Regional Operational Programme (NORTE 2020), under the PORTUGAL 2020 Partnership Agreement, through the European Regional Development Fund (ERDF), within the project "Cybers SeC IP" (NORTE-01-0145-FEDER-000044). This study was also developed as part of the Master in Cybersecurity Program at the Polytechnic University of Viana do Castelo, Portugal.

## References

1. Pending.
2. S. Bezjak, A. Clyburne-Sherin, P. Conzett, P. Fernandes, E. Görögh, K. Helbig, B. Kramer, I. Labastida, K. Niemeyer, F. Psomopoulos, T. Ross-Hellauer, R. Schneider, J. Tennant, E. Verbakel, H. Brinken, and L. Heller, Open Science Training Handbook. Zenodo, Apr. 2018. [Online]. Available: [https://doi.org/10.5281/zenodo.1212496]
3. Ministry of Education and Science of Poland. "Wykaz uczelni publicznych nadzorowanych przez Ministra właściwego ds. szkolnictwa wyższego - publiczne uczelnie akademickie." Nov 2022. [Online]. Available: [https://www.gov.pl/web/edukacja-i-nauka/wykaz-uczelni-publicznych-nadzorowanych-przez-ministra-wlasciwego-ds-szkolnictwa-wyzszego-publiczne-uczelnie-akademickie](https://www.gov.pl/web/edukacja-i-nauka/wykaz-uczelni-publicznych-nadzorowanych-przez-ministra-wlasciwego-ds-szkolnictwa-wyzszego-publiczne-uczelnie-akademickie)
4. RAD-on System. "Dane instytucji systemu szkolnictwa wyższego i nauki." Nov 2022. [Online]. Available: [https://radon.nauka.gov.pl/dane/instytucje-systemu-szkolnictwa-wyzszego-i-nauki](https://radon.nauka.gov.pl/dane/instytucje-systemu-szkolnictwa-wyzszego-i-nauki)
5.  Polish National Agency for Academic Exchange. "List of the university-type HEIs." 2023. [Online]. Available: [https://nawa.gov.pl/images/Aktualnosci/2023/Att.-2.-List-of-the-university-type-HEIs.pdf](https://nawa.gov.pl/images/Aktualnosci/2023/Att.-2.-List-of-the-university-type-HEIs.pdf)
6.  Studies in English. [Online]. Available: [www.studies-in-english.pl](http://www.studies-in-english.pl)

