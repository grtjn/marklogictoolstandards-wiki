Back to [Home](Home)

Status: **Request For Comment** -> Candidate Recommendation -> Standard Recommendation

## Why Needed

A developer should be able to pick up their favourite deploy tool and run the same command there as a deploy tool in a different environment.

## Current situation

Task | Roxy/mlsound | mljsadmin
---- | ---- | ----
Create application scaffolding | init/create | N/A
Initialise tool | init | N/A
Create config files | init | N/A
Print config information | info | N/A
Specify environment configuration to use | CMD ENVNAME | --conf=CONFFILE
Create environment | bootstrap | install
Create REST API instance (content db) | ? | --install=restapi
Create REST API instance (modules db) | ? | --install=modulesrestapi
Deploy ML modules | deploy modules | --install=modules
Deploy web app | deploy modules | N/A (runs in node)
Deploy rest extensions | ? | --install=extensions
Deploy rest resources | ? | N/A
Deploy triggers | ? | --install=triggers $
Deploy alert config | ? | ?
Update search options | ? | --update=searchoptions
Update database configuration (content) | ? | --update=dbconfig
Update database configuration (modules) | ? | --update=modulesdbconfig
Update installed ontology | ? | --update=ontology
Update MLJS Workplace config | ? | --update=workplace $
Copy in content | deploy data | load or --load=/some/folder
Remove content from server | clean | clean
Get config from server | N/A | capture
Get database config (content) | ? | --capture=dbconfig
Get database config (modules) | ? | --capture=modulesdbconfig
Get deployed ontology | N/A | --capture=ontology
Get deployed web app config | N/A | --capture=workplace $
Get deployed search options | N/A | --capture=searchoptions
Get deployed triggers config | ? | --capture=triggers $
Restart MarkLogic | restart | N/A
Run tests | test | N/A
Initialise application to pre-demo state | ? | reset
Removing environment | wipe | remove
Remove REST API (content DB) | ? | --remove=dbconfig
Remove REST API (modules DB) | ? | --remove=modulesdbconfig
Remove REST extensions | ? | --remove=extensions
Remove Triggers | ? | --remove=triggers $

Note that $ means the function requires a server side extension. E.g. REST extension or some other functionality


## Requirements

The system MUST:-

- TODO

The system SHOULD:-

- TODO

The system MAY:-

- TODO

## Recommendation

TODO