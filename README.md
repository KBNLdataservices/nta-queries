# nta-queries
SPARQL queries for the NTA (http://data.bibliotheken.nl/doc/dataset/persons) to be turned into API calls with http://grlc.io/

===============

Input: http://grlc.io/ (service) + eg. https://github.com/KBNLdataservices/nta-queries/blob/main/isni-lookup.rq (SPARQL query)

Output: http://grlc.io/api/kbnldataservices/nta-queries (API)

Docs:
- https://github.com/CLARIAH/grlc
- https://github.com/CLARIAH/grlc/wiki/Quick-tutorial#create-your-linked-data-api
- https://www.slideshare.net/albertmeronyo/grlc-bridging-the-gap-between-restful-apis-and-linked-data

## person-search
(slow)
- http://grlc.io/api-git/KBNLdataservices/nta-queries/person-search?name=mulisch

## nta-lookup
(slow)

## isni-lookup
(slow)
API call examples
- http://grlc.io/api-git/KBNLdataservices/nta-queries/isni-lookup?isni=0000000029132470 (HTML)
- http://grlc.io/api-git/KBNLdataservices/nta-queries/isni-lookup.json?isni=0000000029132470 (JSON)
- http://grlc.io/api-git/KBNLdataservices/nta-queries/isni-lookup.csv?isni=0000000029132470 (CSV)

## viaf-lookup 	
(slow)
- http://grlc.io/api-git/KBNLdataservices/nta-queries/viaf-lookup?viaf=49234516

## wikidata-lookup 	
(slow)

## list-nta-viaf-isni-wdq (1000 nta-ids per page)
- http://grlc.io/api-git/KBNLdataservices/nta-queries/list-nta-viaf-isni-wdq?page=1
- http://grlc.io/api-git/KBNLdataservices/nta-queries/list-nta-viaf-isni-wdq.json?page=3


