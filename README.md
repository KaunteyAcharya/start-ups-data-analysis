## Indian Startup Investment EDA

This repository contains an exploratory data analysis (EDA) of Indian startup funding data. The project cleans mixed-format funding values, parses dates, detects and categorizes startups, investors, and sectors, and derives summary statistics with visual insights.

## Key EDA Features

### Automatic detection of:
-Date column
-Year column
-Amount/funding values
-Startup names
-Investors
-Sectors/industries

### Intelligent parsing:
-Mixed date formats → normalized datetime
-Funding strings with currency symbols, units, M / K suffixes → numeric USD approximation

### Summaries:
-Yearly funding volumes & medians
-Top-funded startups
-Most active sectors
-Most frequently mentioned investors

### Visualizations:
-Missing value heatmap
-Funding trend curves (rounds vs total funding)
-Log-scaled funding distribution
-Sector-wise boxplots
-Top investor frequency bars
-Correlation heatmap for numeric fields
