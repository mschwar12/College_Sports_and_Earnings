# Does the Big Business of College Sports Impact Student Outcomes?
## Predicting post-graduate earnings using University spending behaviors


**Author**: [Matt Schwartz](mailto:mtschwart@gmail.com)

## Overview and Business Problem

The following report provides data and analysis on housing prices in King County, Washington State, and details a number of multiple regression models used to predict these prices. 

## Business Problem

College sports is big business. This biggest schools, like Alabama, Texas, Clemson, and Ohio State generate tens of millions, even hundreds of millions of dollars in revenue across their football and basketball teams. This money has been growing significantly over the past 15 years. From 2006 to 2016, NCAA D1 Football Subdivision (FBS) schools saw overall revenues from increase [to 8.5 billion dollars from 4.4 billion dollars](https://www.ipr.northwestern.edu/documents/working-papers/2020/wp-20-42.pdf). Although these FBS schools (130 schools across 10 major conferences) field 20 or more sports, [58% of total athletic department revenue is derived from men’s football and basketball.](https://www.ipr.northwestern.edu/documents/working-papers/2020/wp-20-42.pdf) What makes these sports even more profitable are the multi-billion-dollar media deals that the major conferences make with networks like ESPN, CBS, and NBC. Conferences like the Big Ten and the SEC even have their own media networks. 

The topic of paying athletes has been the subject of hundreds of articles and numerous economics papers. Instead, I want to explore the connection, if any exists, between what a school spends on its sports programs and the outcomes of its students. Do schools that spend a lot on sports spend less on academics? Do students perform better or worse at major sporting institutions than those that are known more for academic rigor?

Additionally, we'll explore inequality between male and female students. We know about the gender pay gap, but we're not as familiar with how unsupported women's sports and programs are in general at many universities, big and small. Girls and women’s sports have long been underfunded and under-supported for decades, and only started to improve with the introduction of Title IX in 1972. [The title prohibits sex-based discrimination at all schools and programs that receive federal funding.](https://en.wikipedia.org/wiki/Title_IX) It requires schools (colleges in this case) to offer proportional athletic opportunities to men and women. However, compliance falls short despite these regulations. [According to the Women’s Sports Foundation](https://www.womenssportsfoundation.org/wp-content/uploads/2020/01/Chasing-Equity-Full-Report-Web.pdf), 87% of the 1,084 NCAA-participant institutions offered disproportionately higher rates of athletic opportunities to male athletes compared with their enrollment. Division 1 schools fared even worse, with only 8.6% of these institutions offering athletic opportunities to female athletes proportional to their enrollment. 

## Data

We have data from 3 sources:

- [College Athletics Financial Information (CAFI) Database](http://cafidatabase.knightcommission.org/nfs)
This dataset, created by the Knight Commission on Intercollegiate Athletics, captures the expenses and revenues of ahtletic departments across the country. Not all data is accounted for because Private schools are not required to share this information, but the data is complete for all public schools. This dataset has features like total football spending and coaching salaries, student fees collected, ticket sales, and medical expenses. The data consists of all Division 1 schools in the Football Bowl Subdivision (FBS).

- [Equity in Athletics](https://ope.ed.gov/athletics/#/)
This dataset, created by the Office of Postsecondary Education of the U.S. Department of Education. From the website: "The data are drawn from the OPE Equity in Athletics Disclosure Website database. This database consists of athletics data that are submitted annually as required by the Equity in Athletics Disclosure Act (EADA), by all co-educational postsecondary institutions that receive Title IV funding (i.e., those that participate in federal student aid programs) and that have an intercollegiate athletics program. This data allows us to look at how schools are supporting men's and women's sports at very granular detail. We can see how much a school spends on each coach for each t, weamhat the operating expenses are per male and female athlete for each sport, and how many students participate in sports. This will help answer any inequality questions we may have.

- [College Scorecard](https://collegescorecard.ed.gov/)
This dataset is also a product of the Department of Education. It contains many thousands of columns, capturing things like demographics, loan repayment rates, average and median earnings of post-grads, and even average family incomes at each school. Our target - 6 year average earnings, is from this dataset. That feature, captured in 2014-15, contains the average earnings of that school's post-graduates, 6 years after they enrolled at that school. So these are students that started back in 2008-09 and 2009-10.

## Methods

To build a prediction engine, we utilized multiple linear regression.

## Results




## Conclusions



## Further Analysis


## For More Information

Please find the full analysis in the Jupyter notebook contained in this respository.

For any questions, please contact Matt Schwartz at [mtschwart@gmail.com](mailto:mtschwart@gmail.com)



## Repository Structure

```
├── data
├── images
├── .canvas
├── .gitignore
├── CONTRIBUTING.md
├── .pdf
├── .ipynb
├── .pdf
├── README.md
```
