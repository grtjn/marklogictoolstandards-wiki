Back to [Home](Home)

Status: **Request For Comment** -> Candidate Recommendation -> Standard Recommendation

## Why Needed

A developer should be able to pick up their favourite deploy tool and run the same command there as a deploy tool in a different environment.

## Current situation

Task | Roxy | mljsadmin
---- | ---- | ----
Create environment | bootstrap | install
Removing environment | wipe | remove
Deploy ML modules | deploy modules | --install=modules
Deploy web app | deploy modules | N/A (runs in node)
Deploy rest extensions | ? | --install=extensions
Deploy rest resources | ? | N/A
Deploy triggers | ? | --install=triggers
Deploy alert config | ? | ?
Deploy search options | ? | --update=searchoptions
Copy in content | deploy data | load or --load=/some/folder
Remove content from server | clean | clean
Initialise tool | init | N/A
Create config files | init | N/A
Print config information | info | N/A
Get config from server | N/A | capture
Get deployed ontology | N/A | --capture=ontology
Get deployed web app config | N/A | --capture=workplace
Restart MarkLogic | restart | N/A
Run tests | test | N/A


## Requirements

The system MUST:-

- TODO

The system SHOULD:-

- TODO

The system MAY:-

- TODO

## Recommendation

TODO