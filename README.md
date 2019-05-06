recount-brain: a curated repository of human brain RNA-seq datasets metadata
============================================================================

This repository contains the raw files and rendered poster describing the [`recount-brain` project](https://github.com/LieberInstitute/recount-brain) for [Biology of Genomes 2019](https://meetings.cshl.edu/meetings.aspx?meet=GENOME&year=19). This poster was made using [posterdown](https://github.com/brentthorne/posterdown) version 0.1.2.9000 and by customizing the `posterdown_betterport` template provided in that R package. 

To view the poster, go to [https://lcolladotor.github.io/recount-brain-bog19/](https://lcolladotor.github.io/recount-brain-bog19/) or alternatively open the [PDF file](recount-brain-bog19.pdf) which was created using the "print" option with Google Chrome Version 73.0.3683.103 (Official Build) (64-bit).

![](Figures/qr_imglg.png)


## Reproducibility and Citation


```{r}
> ## Reproducibility information:
> library('posterdown')
> library('sessioninfo')
> options(width = 120)
> session_info()
─ Session info ───────────────────────────────────────────────────────────────────────────────────────────────────────
 setting  value                                      
 version  R version 3.5.2 Patched (2019-02-17 r76113)
 os       macOS Mojave 10.14.4                       
 system   x86_64, darwin15.6.0                       
 ui       AQUA                                       
 language (EN)                                       
 collate  en_US.UTF-8                                
 ctype    en_US.UTF-8                                
 tz       America/New_York                           
 date     2019-05-06                                 

─ Packages ───────────────────────────────────────────────────────────────────────────────────────────────────────────
 package     * version    date       lib source                                 
 assertthat    0.2.1      2019-03-21 [1] CRAN (R 3.5.2)                         
 cli           1.1.0      2019-03-19 [1] CRAN (R 3.5.2)                         
 crayon        1.3.4      2017-09-16 [1] CRAN (R 3.5.0)                         
 posterdown  * 0.1.2.9000 2019-05-06 [1] Github (brentthorne/posterdown@00da433)
 sessioninfo * 1.1.1      2018-11-05 [1] CRAN (R 3.5.0)                         
 withr         2.1.2      2018-03-15 [1] CRAN (R 3.5.0)                         

[1] /Library/Frameworks/R.framework/Versions/3.5/Resources/library
> 
> ## Citation information for recount-brain
> citation('recount')[5]

Razmara A, Ellis SE, Sokolowski DJ, Davis S, Wilson MD, Leek JT, Jaffe AE, Collado-Torres L (2019).
“recount-brain: a curated repository of human brain RNA-seq datasets metadata.” _bioRxiv_. doi:
10.1101/618025 (URL: http://doi.org/10.1101/618025), <URL: https://doi.org/10.1101/618025>.

A BibTeX entry for LaTeX users is

  @Article{,
    title = {recount-brain: a curated repository of human brain RNA-seq datasets metadata},
    author = {Ashkaun Razmara and Shannon E. Ellis and Dustin J. Sokolowski and Sean Davis and Michael D. Wilson and Jeffrey T. Leek and Andrew E. Jaffe and Leonardo Collado-Torres},
    year = {2019},
    journal = {bioRxiv},
    doi = {10.1101/618025},
    url = {https://doi.org/10.1101/618025},
  }

> 
> ## For posterdown:
> citation('posterdown')

To cite 'posterdown' in publications use:

  W. Brent Thorne (2019). posterdown: An R Packge. R package version 0.1.2.9000.

A BibTeX entry for LaTeX users is

  @Manual{,
    title = {posterdown: An R Package Built to Generate Reproducible Conference Posters for the Academic and Professional World Where Powerpoint and Pages Just Won't Cut It},
    author = {W. Brent Thorne},
    year = {2019},
    url = {https://github.com/brentthorne/posterdown},
    note = {R package version 0.1.2.9000},
  }

> 
```
