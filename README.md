# -- HATHI TRUST TORCH-LITE HACKATHON -- #
## Hathi Trust Documents Used in Education ##

### Hackathon collaboration between:### 

-  [Tim Bowman](https://www.dom.edu/directory/tim-bowman), Associate Professor, Dominican University, School of Information Studies [ORCID](https://orcid.org/0000-0003-0247-4771)
-  [Kai Li](https://sis.utk.edu/about/directory/kai-li), Assistant Professor, University of Tennessee, School of Informaiton Science [ORCID](https://orcid.org/0000-0002-7264-365X)

## OVERALL GOALS ##
1. Determine how Hathi Trust books are used in Syllabi for educational purposes

2. Determine what academic domains are using the documents

3. Deteremine how difficult the documents are to read


![Mind Map of Hackathon Project Mashup](images/Mind%20map%20with%20lines.png)


## HACKATHON INFO ##

- [Torch-Lite Hackathon](https://htrc.github.io/torchlite-hackathon/)


## DATA SOURCES ##

- [GitHub - Amir Motavas - Open-Syllabus Repo](https://github.com/mtdamir/open-syllabus/tree/master)
  - [GitHub Starting Point {Classics} List of Docs}](https://raw.githubusercontent.com/mtdamir/open-syllabus/master/urls.csv)
 
- [Open Syllabus](https://docs.opensyllabus.org/index.html)
  - [Open Syllabus Example JSON Record](https://explorer-api.opensyllabus.org/v1/works/50903952394903.json)
    
- [Open Library](https://openlibrary.org/)
  - [Open Library Example JSON Record](https://openlibrary.org/search.json?title=Metamorphoses&author=Ovid)
 
- [Goodreads API {deprecated but still working} ](https://www.goodreads.com/api)
  - [Goodreads API JSON Record](https://www.goodreads.com/book/review_counts.json?isbns=2080720929)
 
- [Hathi Trust Library APIs](https://www.hathitrust.org/member-libraries/resources-for-librarians/data-resources/)
  -  [Hathi Trust Metadata JSON Record](https://catalog.hathitrust.org/api/volumes/full/recordnumber/009709406.json)
  -  [Hathi Trust EF JSON Record](https://data.htrc.illinois.edu/ef-api/volumes/hvd.32044090286501)



## RESULTS ##

1. Matched 306 of 999 books from Open Syllabi lists to Hathi Trust catalog

2. Visualizations demonstrate in what academic domains the Hathi Trust documents are being used (without exact matching to edition)
   
3. Calculates [Flesch-Kincaid Readability and Grade Scores](https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests) for each document
   1. [Flesch Reading Ease](https://readable.com/readability/flesch-reading-ease-flesch-kincaid-grade-level/)

4. We analyzed Hathi Trust Metadta subject headings
     1. Idea is to compare document SH with academic domains in which document is assigned
  
5. We grabbed Goodreads review data to see ranking of book
    1. Idea is to then grab actual text reviews to analyze how the "public" rank and talk about the documents
  
   
 

