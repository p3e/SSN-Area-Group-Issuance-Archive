# SSN Area-Group Issuance Archive

A  historical archive of Social Security Number (SSN) area-group combinations and their issuance dates, compiled from official SSA High Group Lists (1936-2011).

## Overview

This archive contains detailed records of when specific SSN area-group combinations were issued across all 50 U.S. states and Washington DC. The data covers the period from the first SSN issuance in 1936 through June 24, 2011, when the Social Security Administration implemented SSN randomization.

## What's Included

- **51 CSV files** organized by state/territory
- **Complete area-group combinations** (xxx-yy format) with issuance dates
- **Year ranges** showing when each combination was first and last issued

## Data Structure

Each CSV file contains the following fields:

```csv
SSN Prefix,Years Issued
268-01-####,1936-1950
268-02-####,1996-1998
268-03-####,1936-1950
268-04-####,1998-unknown
```

### Fields:
- **Social Security Number**: Area-group combination in format `xxx-yy-####`
- **First Year Issued**: Year this area-group was first assigned
- **Last Year Issued**: Year this area-group was last assigned (or "unknown" if still in use until 2011)

## File Organization

```
tables/
├── alabama.csv
├── alaska.csv
├── arizona.csv
├── california.csv
├── ohio.csv
└── ... (51 total files)
```

## Historical Context

### SSN Structure (Pre-2011)

Social Security Numbers consist of three parts:

1. **Area Number (xxx)**: First 3 digits - indicated the geographic region where the SSN was issued
2. **Group Number (yy)**: Middle 2 digits - assigned in a specific non-consecutive order:
   - Odd: 01-09
   - Even: 10-98
   - Even: 02-08
   - Odd: 11-99
3. **Serial Number (####)**: Last 4 digits - assigned sequentially within each area-group

### SSN Randomization (June 25, 2011)

On June 25, 2011, the SSA implemented SSN randomization, eliminating the geographic significance of area numbers and the predictable issuance pattern of group numbers. **This database only covers SSNs issued before this date.**

## Use Cases

- **Genealogy Research**: Determine when and where ancestors received their SSNs
- **Identity Verification**: Validate SSN area-group combinations against known issuance patterns
- **Historical Analysis**: Study SSN issuance patterns across different time periods and regions
- **Data Science**: Analyze demographic patterns in SSN distribution
- **Educational**: Understand the historical structure and evolution of the SSN system

## Data Sources

This archive was compiled from:
- Official SSA High Group Lists (monthly publications, 1936-2011)
- SSA area number allocation tables
- Historical SSN issuance records from SSA.gov
- Data aggregated and published by SSN-Verify.com

## Important Notes

### Privacy & Legal Considerations

- This database contains **no personally identifiable information (PII)**
- Only area-group combinations are included (no serial numbers)
- This data cannot be used to identify specific individuals
- All information is derived from publicly available SSA publications
- **Use responsibly and in compliance with applicable laws**

### Data Limitations

- Only valid for SSNs issued **before June 25, 2011**
- SSNs issued after this date follow randomized patterns
- Some area-group combinations may have gaps or inconsistencies in historical records
- "Unknown" last year typically indicates the combination was still in use until 2011

## Contributing

Contributions are welcome! If you find errors or have additional historical SSN data:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request with detailed documentation

### Reporting Issues

- Data discrepancies
- Missing area-group combinations
- Historical inaccuracies

Please open an issue with specific details and sources.

## License

This data is compiled from public domain sources (official U.S. government publications).

### Attribution

If you use this database, please cite:
```
SSN Area-Group Issuance Archive
Compiled from SSA High Group Lists (1936-2011)
https://github.com/p3e
```

## Acknowledgments

- Social Security Administration for publishing historical high group lists
- SSN-Verify.com for data aggregation
- Jerry Crow and Barbara Bennett for pioneering SSN structure research
- The genealogy and research community for preserving historical records
- Steven Morse, for giving me the urge to create this so I wouldn't get rate limited

## Disclaimer

This database is provided for historical, educational, and research purposes only. The maintainers make no warranties about the accuracy, completeness, or reliability of this data. This tool should not be used for illegal purposes, identity theft, fraud, or any activity that violates privacy laws or regulations.

**The SSN system changed fundamentally in 2011. This data is historical only.**

## Contact

For questions, corrections, or collaboration:
- Open an issue on GitHub
- https://github.com/p3e

## Version History

- **v1.0.0** (2025-10-01): Initial release with complete 1936-2011 data

---

**Last Updated**: October 2025  
**Data Coverage**: November 1936 - June 24, 2011
