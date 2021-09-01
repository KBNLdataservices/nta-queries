# nta-queries
SPARQL queries for the NTA (http://data.bibliotheken.nl/doc/dataset/persons) to be turned into API calls with http://grlc.io/

===============

Input: http://grlc.io/ (service) + eg. https://github.com/KBNLdataservices/nta-queries/blob/main/isni-lookup.rq (SPARQL query)

Output: http://grlc.io/api/kbnldataservices/nta-queries (API)


## ISNI lookup
API call examples
- http://grlc.io/api-git/KBNLdataservices/nta-queries/isni-lookup?isni=0000000029132470 (HTML)
- http://grlc.io/api-git/KBNLdataservices/nta-queries/isni-lookup.json?isni=0000000029132470 (JSON)
- http://grlc.io/api-git/KBNLdataservices/nta-queries/isni-lookup.csv?isni=0000000029132470 (CSV)

## Person lookup
- http://grlc.io/api-git/KBNLdataservices/nta-queries/person-lookup?name=mulisch

Docs:
- https://github.com/CLARIAH/grlc
- https://www.slideshare.net/albertmeronyo/grlc-bridging-the-gap-between-restful-apis-and-linked-data

