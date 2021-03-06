# Writing Reproducible Research Papers with R Markdown

This repository holds the materials for a workshop on writing reproducible research papers with R Markdown, first taught at [Campus Luzern](https://www.campus-luzern.ch/) in March 2020, revised in April 2020.


## Substance

The workshop is divided into nine parts, with an additional part on *colloboration* in the making. Most parts include exercises &mdash; 35 in total.

**Part 1. Getting the Tools Ready**
   - e.g., downloading course material

**Part 2. Introducing R Markdown**
   - e.g., creating a new document

**Part 3. Setting Metadata**
   - e.g., defining output format

**Part 4. Writing Text**
   - e.g., adding emphasis to text

**Part 5. Managing References**
   - e.g., citing sources

**Part 6. Adding Code, Figures, and Tables**
   - e.g., plotting data

**Part 7. Addressing Functionality Gaps**
   - e.g., adjusting line spacing

**Part 8. Using Version Control**
   - e.g., integrating Git and GitHub

**Part 9. Working on a Real Project**
   - e.g., converting a work-in-progress of yours
   

##  Material

- `manuscript/reproduce_this.pdf`
    - a document, formatted in Word but saved as PDF, to be re-created with R Markdown 
    - random sentences in the document are generated with the `stringi` package  (Gagolewski, 2020)
    - figures and tables are based on a fabricated dataset (`journals.csv`, see below)
    - key sections in-need of attention are highlighted

- `manuscript/journals.Rmd`
    - an R Markdown document to work on during the workshop
        - includes unformatted text from `reproduce_this.pdf` to save time
        - major components, such as paragraphs and tables, are numbered and marked in comments to facilitate navigation
        
- `manuscript/references.bib` 
    - a BibTeX document with three fabricated references
    
- `manuscript/apa_7th.csl`
    - a Citation Style Language document, with APA (7th Edition) referencing style (Wiernik, 2020)

- `data/journals.csv`

    - a dataset created with the `fabricatr` package (Blair et al., 2019), imagined to explore the Google Scholar rankings of fictitious journals
    
    - includes the following variables 
        - **name**: journals (1090 random titles)
        - **origin**: geographic origins (five continents)
        - **branch**: major discipline of journals (four branches)
        - **since**: time of first publication (years)
        - **h5_index**: H5 Index (integers)
        - **h5_median**: H5 Median (integers)
        - **english**: English (1) *vs.* other-language (0) journals
        - **subfield**: subfield (1) *vs.* generalist (0) journals
        - **issues**: number of issues published per year (integers)
   

- `image/google_scholar.png`
    - a screeenshot image of the Google Scholar homapage

- `presentation/rmd_workshop.pdf`
    - slides in PDF format
    - HTML version is available at <https://resulumit.com/teaching/rmd_workshop.html>
        - offers, among others, the ability to scroll across long codes on some slides

 
## References

Blair, G., Cooper, J., Coppock, A., Humphreys, M., Rudkin, A. and Fultz, N. (2019). [fabricatr: Imagine your data before you collect it](https://cran.r-project.org/web/packages/fabricatr/index.html). R package, version 0.10.0.

Gagolewski, M. (2020). [stringi: Character String Processing Facilities](https://cran.r-project.org/web/packages/stringi/index.html). R package, version 1.4.6.

Wiernik, B. M. (2020). [American Psychological Association 7th edition (no ampersand)](https://www.zotero.org/styles/apa-no-ampersand). Citation style language file, version 1.0.