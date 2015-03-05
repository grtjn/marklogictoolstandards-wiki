[Home](Home)

Status: **Request For Comment** -> Candidate Recommendation -> Standard Recommendation

## Why needed

A standard foldering layout will allow inclusion of all MarkLogic application configuration within any build tool framework, and provide consistency. A single app layout will be deployable within a variety of tools.

## Requirements

The system MUST:-

- Use a single, uniquely named, parent folder so as to minimise the interference with build tool specific folder layouts
- Store all MarkLogic configuration, runtime, database exports, data, and everything else for the MarkLogic application within that structure
- Store different classes of configuration under sub folders
- Support at least a single environment (MarkLogic server settings), packaging API configuration, content to load

The system SHOULD:-

- TODO

The system MAY:-

- TODO

## Recommendation
