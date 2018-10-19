# Structural Analysis
### Objectives
- Start Talend Studio
- Browse Profiling Perspective
- Store DB Connections Details as metadata
- run an overview analysis

### DQ Repository
- Data Profiling - create analysis and reports
- Libraries/Exchange - Store additional resources (paterns, rules, template)
- Metadata - stores connection info, table metadata, etc.

### New Analysis
- 5 Subsets
- Each one matches an analysis type from pt1
- around 3-5 job templates per analysis type

### Structural Analysis Category
- Content of a db server (this is interesting, gives high level database details, run this against mysql)
- content of a catalog (I missed this)
- content of a schema (number of tables, size of data, etc. on a per schema basis)

# Column Analysis
- Unique, distinct, duplicate value count
- pattern frequencies
- regex matching
- data belongs to which domain (semantic) ex. PID data

### Analysis Enhancements
- Rgex patterns
- Indicator Thresholds
- Advanced Stats (data frequency indicators)
- All analysis run in local environment (memory constraints with high volume datasets)

# Table Analysis Category (Continued)
- Column Set Analysis
- Business Rule Analysis (how does this work?)
- Functional Dependency Analysis
- Match Analysis

- This section was useful for
-- Checking for matches, or errors, in more than one column of a table
-- Creating sql business rules and applying them to your analysis
-- Doing a business rule based on a foreign constraint

# Cross Table Analysis
- 1-n or 1-1 relationship
- Pri or FK matching
- Corelational Analysis
-- looking for weird data fluctuation compared to existing data
- there's some cool graph stuff here
