# Data Quality Markers
- Validity
- Accuracy
- Integrity
- Completeness
- Consistentcy
- Timeliness

## Validity

## Accuracy

## Timeliness
- Data should be available for all timelines (i.e. we have no data for March)

## Consistency
- Is the data consistent across systems?
- i.e. True/False flag always tinyint 1/0

## Completeness
- Missing values for certain dimensions (i.e. what is a person's age)

## Integrity
- Data could be valid, but wrong. I.E. Misentering a zip code

# Data Quality Process
Source Data -> Data Profiling -> Data Cleansing -> High Quality Data

# Five Analysis Categories
## Structural Analysis
- Overview of database content

## Column Analysis
- indicator selection according to data type (pattern frequences, regex matching)

## Table Analysis

## Cross Table Analysis
## Correlation Analysis
