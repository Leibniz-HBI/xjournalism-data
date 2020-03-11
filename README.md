## xJournalism Data Queries
Data collection on our glossary of journalism terms via various sources e.g.   
Times API, Wikidata, Google Scholar, Google nGrams, Ebsco.
  
https://xjournalism.org

### Prerequisites

1. Node 8.10+
4. GCP Service Account
5. Enabled Sheets API

### Develop
```bash
npm i # install deps
touch {service_account}.json # add gcp credentials
node index.js
```    

### Todo
- [x] Add Wikidata Query Hits
- [x] Add NYTimes Search API Metadata
- [x] NYTimes Oldest Article Dates
- [x] Move to sanitized, denormalized keys/uids

### Author
Paul Solbach, Leibniz HBI  
<p.solbach@leibniz-hbi.de>
