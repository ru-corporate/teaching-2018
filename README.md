# teaching-2018

Instructor resources for "Machine-readable corporate financial statements" course

TODO
====

- send out an VK link + video (FB, ostov)
- co-instructors 
- course reviewers
- dividends repo

Theory of the firm:
===================

- [Corporate Finance, Incomplete Contracts, and Corporate Control](https://www0.gsb.columbia.edu/mygsb/faculty/research/pubfiles/6023/CFICCCrevision3.pdf)
 

Instructor outline - 2018
=========================

Team roles
----------

    ------------------------------------------------------------------

    Data access      ***********
    Clean dataset          ***********
    Analysis                    ********************
    Presentation                             ****************
    Dessemination                                      ***************  
    Research / business value                                       (@)

    ------------------------------------------------------------------

    Profit: replicable result, control of data pipeline  


- ETL (data engineer) -> API endpoint
- statistics analyst -> data map 
- financial analyst -> empriric financial ratios
- researcher -> list of use cases and research questions 
- visualisation expert -> all charts 
- *scientific publisher* -> format for publication output  
- writer/editor/proof reader
- outreach/PR -> citations

Excercises
----------

- review of agile methodologies 
- ds cookiecutter
- top 3 questions for perfect dataset 
- review scientific publishing methodologies

Learning objectives
-------------------

- ORG: course organisation 
   - thesis + data-model-view
   - data + excercise + finding + decision case 
   - slim end-to-end data pipeline build first
   - 'agile' methodologies

- INTRO-FIN:
   - corporate reporting and disclosure procedures
   - financial statements use cases 
   - available aggregate data sources and their limitations
   - refresher on accounting
   - theory of firm, continious reporting, continious assurance   

- INTRO-DS:
   - research as a data pipeline (using ds cookiecutter)
   - presentation and delievery of research (open topic)

- ETL: load, inspect and clean large tabular dataset  
   - load data from immutable source 
   - perform data consistency checks (control datapoints, identities, outliers)
   - transform data 
   - create and document access endpoints (API)

- STAT: estimate dataset coverage ratios with respect to other statistics sources
   - define and compute comparison metrics (value added, output, debt, fixed assets) 
   - access comparison datasets
   - represent several dimensions of coverage on a chart (map)


\*\*\* TODO:  add part 2, 3 \*\*\*

Stages:

    - Part 1: Data preparation (ETL + validation): data analyst
    - Part 2: Excercises, research findings and business cases (EDA - problem space - solutions): researcher/business analyst
    - Part 3: Viz, frontend and presentation (notebook, interactive apps, docs, pdfs, etc.): 'artist'/'releaser'/'editor'/'frontend specialist'

Financial statements only:

    - understanding bookkeping, double entry, company financial statements as queries general ledger  
    - capital structure 
    - profitability
    - liquidity, cash flows 
    - bankruptcies
    - fixed assets returns, costs and productivity 

Additional datasets (market, official stats, tax, other):

    - equity and bond prices
    - employment
    - R&D 
    - physical output
    - foreign ownership
    - industrial stats
    - tax reciepts
    - real-time data
    - machine-readable registries
    - news clips and good recearch article references

Corporate map:

    - GDP / industries / regions boundary values (official stats)
    - stock and bond market stats
    - other layers

Use cases:

    - value a firm (M&A, investment)
    - price borrowing to firm (bonds, bank credit)
    - find investment/aquisition targets (private equity)
    - predict default events (bank loan monitoring, EWS)
    - benchmark project or firm performance (stakeholders)
    - make a business plan (startups)
    - find new clients (business services)
    - evaluate policies (eg taxation, subsidies)
    - initiate voluntary disclosure and formats (reporting requirements)
    - analyse market structure, industries, regional businesses, SMEs  

Chapters:

    About authors

    1. What do we have covered?
    - dataset imperfections
    - scope and validation of dataset 
    - corporate Russia : map and gaps

    2. Large corporations
    - who grows?
    - who invests?
    - how firms finance?
    - who defaults?
    - typical financial ratios

    3. Subsets: SME, industries, regions
    - how industries are different?
    - how are SMEs are doing?
    - how regions are different?

    4. Conclusions

    Appendix     
    - how to reproduce this dataset for your own research    
    - artefects: firm names
    - excercise: replicate Expert 200 list
    - methodolody: what if we had perfect information? can we have perfect information (best practices in disclosure and open stat)?
    - access alternatives: BIR, SPARK, СКРИН

Checkpoints:

    - [ ] dataset downloadable
    - [ ] dataset clean (with tests)
    - [ ] can compute firm metrics
    - [ ] can make subsets of companies 
    - [ ] list hypothesis and findings formulated
    - [ ] options for visualisation defined
    - [ ] prose written, edited, accepted
    - [ ] output format defined and accepted
    - [ ] report cited citations 
    - [ ] accepting new questions from use cases, acticle replication, controversies, news, etc
    - [ ] author credentials written
    - [ ] student feedback collected

Collaboration tools:

    - slack (?) 
    - github, s3 (no dropbox)
    - trello board (?)

To add:

    - course descriptions
    - video Link
    - previous teaching
    - self-study guides

Not covered:

    - РСБУ vs IFRS
    - networks, cross ownership, business groups 


Sister projects:
    - mini-kep    
    - GIS regional maps
    - dividend reporting 

Links bulk:


- [Who uses corporate reports](http://eprints.lse.ac.uk/57683/1/__lse.ac.uk_storage_LIBRARY_Secondary_libfile_shared_repository_Content_Cascino%2C%20S_Who%20uses%20financial%20reports_Cascino_Who%20uses%20financial%20reports_2015.pdf)
- [Damodaran hands-on project](http://people.stern.nyu.edu/adamodar/pdfiles/cfovhds/cfproj.pdf)
- [Twitter Corpfin](https://ideas.repec.org/i/etcfn.html)

---

- http://www.scielo.org.mx/pdf/cys/v21n4/1405-5546-cys-21-04-00809.pdf
- https://www.bcg.com/publications/2018/global-corporate-banking-2018-unlocking-success-through-digital.aspx
- https://fulyankin.github.io/cmf_part2/
- https://ocw.mit.edu/courses/civil-and-environmental-engineering/1-040-project-management-spring-2009/lecture-notes/MIT1_040s09_lec08.pdf
- https://pdfs.semanticscholar.org/e87c/e5bf38a7a1390d3a0713a4bb035585b804bb.pdf
- http://www.corpfin.ugent.be/teaching/topicsincorporatefinance/
- https://faculty.chicagobooth.edu/raghuram.rajan/research/papers/The%20Corporation%20in%20Finance%20ver8.pdf
- http://www.nber.org/papersbyprog/CF.html
- https://www.forbes.com/sites/forbestechcouncil/2018/05/01/the-robots-are-coming-to-corporate-finance/#44c137c056b6
- https://www.ey.com/Publication/vwLUAssets/EY_-_Robotic_process_automation_in_the_Finance_function_of_the_future/$FILE/EY-robotic-process-automation-in-the-finance-function-of-the-future-2016.pdf
- https://github.com/search?q=corporate+finance

---

> Use URIs to identify data. Uniform Resource identifiers (URIs) are a type of web link. They make it easier for your users to point at and draw upon your data.
[*](https://data.wa.gov.au/junk/fact-sheets-and-toolkit/creating-machine-readable-data)

---

Exploratory Data Analysis (EDA):

- set of approaches / philosophy / some phsycology 
- developed at start computer age, puts reasoning before computing, plotting by hand  
- traditional components: residual analysis, data re-expression, resistant procedures, and data visualization.
- newer components: clustering, variable screening, and pattern recognition

> Exploratory data analysis’ is an attitude, a 
> state of flexibility, a willingness to look for 
> those things that we believe are not there, as 
> well as those we believe to be there.


Reading:
- data is uncertain (measurement error, experiment bias, falsification, data corruption)
- our reading of data is prejudiced 
- it takes effort to clean data + extract knowledge from data

```
R: summary(data)
pandas: df.describe()
```

Examples:
- https://www.kaggle.com/ekami66/detailed-exploratory-data-analysis-with-python


Links:

- [EDA Berkley](https://www.stat.berkeley.edu/~brill/Papers/EDASage.pdf)
- [](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1332871/?page=7)
- [EDA in Handbook of Statistical Methods](https://www.itl.nist.gov/div898/handbook/eda/eda.htm)
- [Exploratory data analysis and Data visualization by Chong Ho Yu](http://www.creative-wisdom.com/teaching/WBI/EDA.shtml)
- [Exploratory Data Analysis by Chong Ho Yu](http://www.oxfordbibliographies.com/view/document/obo-9780199828340/obo-9780199828340-0200.xml?rskey=JOlkN9&result=50)

---

DataViz:

- https://www.kaggle.com/learn/data-visualisation
