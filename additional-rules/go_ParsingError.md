# Go Parser Failure

## Rule Details

- **Rule ID:** go:ParsingError  
- **Analysis Scope:** All sources  
- **Rule Repository:** Sonar (Go)  
- **Effort:** 30 minutes  
- **Type:** Code Smell  
- **Severity:** Major  
- **Tags:** Suspicious, Clean Code  
- **Attribute:** Consistency | Conventional  
- **Software Qualities Impacted:** Maintainability  

## Why is this an Issue?

When the parser fails, it is possible to record the failure as an issue on the file. This allows tracking the number of files that do not parse and provides insight into why they fail. Addressing these parsing failures ensures better maintainability and prevents potential issues in code analysis.

