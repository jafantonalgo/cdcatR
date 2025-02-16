cdcat 1.0.3:

## cdcatR 1.0.3 release (July 6, 2021)
* We have included new arguments for the cdcat and gen.itembank functions of the package

## cdcatR 1.0.2 release (September 9, 2020)
* Fixed minor bugs for the cdcat() function
* We get this note: "> checking for future file timestamps ... NOTE
  unable to verify current time". I believe this is related to the check function 

## cdcatR 1.0.1 release (July 1, 2020)
* CRAN Package Check Results found an issue for noLD. We have corrected this [if (sum(probs) != 1) {] has been replaced]. Thanks Prof Brian Ripley and CRAN

## Second resubmission (June 8, 2020)
* We have addressed the only concern mentioned in the mail we got on June 2, 2020 (thanks Swetlana Herbrandt). Specifically, 
* We have includeda small executable (not wrapped in \dontrun or \donttest) example for the main function (i.e., cdcat()). It is wrapped in \dontshow so that this informal test is not shown in the help page
* We now use \donttest instead of \dontrun for examples that take longer than 10 seconds. We have checked that all the examples work fine  

## First sesubmission (May 26, 2020)
* We have addressed the two concerns mentioned in the mail we got on May 25, 2020 (thanks Jelena Saf). Specifically, 
* We have removed the redundant "in R" from the title
* A more elaborate package description was added in the description field of the DESCRIPTION file. Some references were included
* TRUE and FALSE are now always used instead of T and F. No variables are named T or F 

## Test environments
* local Windows installation, R 3.6
* Ubuntu Linux 16.04 LTS, R-release, GCC (check_rhub)
* Windows Server 2008 R2 SP1, R-devel, 32/64 bit (check_rhub)
* Fedora Linux, R-devel, clang, gfortran (check_rhub)
* (check_win_devel)

## R CMD check results
There were no ERRORs or WARNINGs. 

There was 1 NOTE:

* Maintainer: ‘Miguel A. Sorrel <miguel.sorrel@uam.es>’
  
  New submission
  Possibly mis-spelled words in DESCRIPTION:
    Barrada (7:277)
    Chiu (7:371)
    Abad (7:689)
    Kaplan (7:252)
    Olea (7:698)
    Tsai (7:381)
    de (7:260, 7:676)
    
* Please note thate these words are surnames. The spelling is correct
