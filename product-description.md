M2 Money Stock | FRED
=========================

The source code outlining how this product gathers, transforms, revises and publishes its datasets is available at [https://github.com/rearc-data/fred-m2-money-stock](https://github.com/rearc-data/fred-m2-money-stock).


## Main Overview

This release contains information on M2, which consists of M1, savings deposits, small-denomination time deposits, and balances in retail money market mutual funds. Since this is seasonally adjusted, M2 is computed by summing the latter three factors up, which are seasonally adjusted individually, which will then be added to a seasonally adjusted M1. M2 is held mainly by households.

The included data is provided by the Federal Reserve Bank of St. Louis' FRED (Federal Reserve Economic Data) platform, which contains information on over 700,000+ series related to historical economic data. If you are interested in learning more or want to explore other datasets maintained on FRED, visit the [FRED homepage](https://fred.stlouisfed.org/).


#### Data Source

This resource is presented in both the XLS and CSV formats. The included dataset contains the following columns:

`date, M2`

The `M2` column represents billions of dollars of M2 at the time of the corresponding `date`.  


## More Information
- Source: [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/series/M2)
- [FRED | Federal Reserve Bank of St. Louis](https://fred.stlouisfed.org/)
- [Federal Reserve Bank of St. Louis | Homepage](https://www.stlouisfed.org/)
- [Terms of Use FAQ](https://fred.stlouisfed.org/legal/)
- Frequency: Monthly
- Formats: XLS, CSV

## Contact Details
- If you find any issues with or have enhancement ideas for this product, open up a GitHub [issue](https://github.com/rearc-data/fred-m2-money-stock/issues) and we will gladly take a look at it. Better yet, submit a pull request. Any contributions you make are greatly appreciated :heart:.
- If you are looking for specific open datasets currently not available on ADX, please submit a request on our project board [here](https://github.com/rearc-data/covid-datasets-aws-data-exchange/projects/1).
- If you have questions about the source data, please contact .
- If you have any other questions or feedback, send us an email at data@rearc.io.

## About Rearc
Rearc is a cloud, software and services company. We believe that empowering engineers drives innovation. Cloud-native architectures, modern software and data practices, and the ability to safely experiment can enable engineers to realize their full potential. We have partnered with several enterprises and startups to help them achieve agility. Our approach is simple — empower engineers with the best tools possible to make an impact within their industry.
