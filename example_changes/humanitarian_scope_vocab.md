# Example Standard Change

## Current Rule

[Humanitarian Scope Vocabulary](https://iatistandard.org/en/iati-standard/203/codelists/humanitarianscopevocabulary/)

The Humanitarian Scope Vocabulary codelist defines a range of external codelists which themselves provide codes and descriptions for humanitarian events and actions.

This is a Non-Core codelist.

Allowed values are:
* 1-2 (Glide)
* 2-1 (Humanitarian Plan)
* 99 (Reporting Organisation)

## Proposed Change

That the values are replaced with numeric values: 12, 21, 99.

## Rationale

Microsoft Excel interprets 1-2 and 2-1 as dates, which makes it hard to work with IATI data that uses this codelist in spreadsheets. 

## Impact

Any data that uses this codelist would become invalid. This would cause data without any other issues to move from “Success” to “Error” status on the IATI Validator. 

Once data has been converted to use the new values, data analysis using this codelist in spreadsheet software will be more straightforward. 

Currently (Sept 2024), 44 publishers use this codelist to describe ~22,000 activities.