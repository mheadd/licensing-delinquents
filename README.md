## Licensing Delinquents

Data from a December 2013 study conducted by the open data team in the City of Philadelphia examining building permits and rental licenses issued to properties with an overdue property tax balance.

The <code>permits</code> file is unique by Permit or License Application, where some addresses and their collectible tax balances are listed more than once if multiple applications were issued.

The <code>addresses</code> file is unique by Address with collectible tax balances included.

At the time of this analysis (December, 2013) there were 9,251 Permits or Licenses issued to properties with outstanding tax balances, and 5,969 properties that had been issued permits or licenses that were tax delinquent at the time of issuance, and were still delinquent at the time of the analysis for a total of over $48M collectible.

### Why Release This Data?

Though the analysis that produced this data was still in its infancy, the preliminary findings clearly demonstrate the need for better data integration in the City of Philadelphia. An open strategy focused on developing simple to use, well documented APIs for external users will produce an environment where data sharing between city departments (like Revenue and L&I) can take place easily and efficiently.

Hopefully, the data included in this repo will help illuminate the costs of not pursuing such a strategy.

### Caveats

This analysis was conducted several months ago, so the outstanding tax balances included in the files in this repo may have changed.

Permit & License data for the City of Philadelphia is available via a REST API [detailed here](http://phlapi.com/licenseapi.html).

Property tax balance data is not currently available via a public API but information on individual properties my be seen on the Philadelphia [Department of Revenue website](http://www.phila.gov/revenue/realestatetax/). In addition, an unofficial extract of property tax balance information can be obtained from [this site](http://www.philadelinquency.com/). As part of the analysis that produced this data, an internal test environment with tax balance information was used.

The analysis that produced this data was still in progress when work on it stopped. It is possible that further work may have refined the accuracy of the information contained in this repo, or produced more data.