# Example Standard Change

## Current Rule

A number of rules in the IATI Standard Ruleset state that the iati-identifier should not start or end with spaces or a newline. 

## Proposed Change

That instances of “should” be replaced with “must”.

## Rationale

Identifiers that start or end with spaces or newlines are likely to cause processing issues for data consumers, and can be difficult (or impossible) to search for. 

It is likely that such characters are the result of input or processing errors, rather than genuine components of an identifier. 

## Impact

Any data that has identifiers that start or end with spaces or newlines would move from having “Warning” status to “Error” status. Such data will still be present in the IATI Datastore but any data quality reporting based on the IATI Validator will show the new status. 

If publishers respond to the change by removing such characters, the overall quality of IATI data will improve through better-quality identifiers, which are the foundation of much data analysis. 

Currently (Sept 2024) there are ~6600 activities from 50 publishers that would be affected.