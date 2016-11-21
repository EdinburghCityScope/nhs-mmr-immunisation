# nhs-mmr-immunisation
## Measles Mumps Rubella (MMR) Immunisation

Number, and percent of, children who have received 1 dose of Measles, Mumps and Rubella (MMR) vaccine by 5 years of age. [Publication](http://isdscotland.org/Health-Topics/Child-Health/Publications).

It should also be noted that children with a missing or invalid postcode have been excluded. As a result uptake rates may not exactly match those already published on the ISD Child Health Immunisations page.

Source: Scottish Immunisation and Recall System (SIRS), ISD Scotland. http://statistics.gov.scot/data/measles-mumps-rubella

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nhs-mmr-immunisation.git
```

Install npm dependencies

```
cd nhs-mmr-immunisation
npm install
```

Run the API (from the nhs-mmr-immunisation directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
