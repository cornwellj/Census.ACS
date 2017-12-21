# Census.ACS
## Intro
Census and ACS analysis code 

This repository contains code to pull data from and analyze data from a variety of Census Bureau datasets. The Census Bureau has a wide array of products in addition to the Decennial Census, including the American Community Survey (ACS), American Housing Survey (AHS) and many others.

The code in this repository is built around the package **censusapi**. **censusapi** is an accessor package for the United States Census Bureau's APIs - APIs or application programming interfaces are tools that allow us to access data from online repositories (they are more than that but that is all we really need to know for this repository). 

As of 2017 there are more than 200 Census API endpoints available, **censusapi** lets us get data from all of those APIs using the same main function _getCensus_ and the same syntax for each dataset.

Accessing the Census APIs wit **censusapi** requires an API key.

Evergreen has a CensusAPI key - 65391b6bd098e99a339604c4ea74d6630e4e4f94
Step one installs the package and loads the API key.

## 1 - Load **apicensus** and install API key

1) Run Census.ACS.AddAPIKey
