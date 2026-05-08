# NFT Market Analysis

A comprehensive data-driven analysis of NFT market trends and their correlation with cryptocurrency markets using R and statistical analysis.

## Project Overview

This project explores and analyzes NFT market trends to understand market dynamics and predict future developments. Through rigorous statistical analysis and data visualization, we examine the relationship between NFT interest and cryptocurrency markets using real-world search interest data.

**Key Insight**: We discovered a significant positive correlation between NFTs and cryptocurrency interest, though data availability currently limits reliable market predictions.

## Objectives

- Analyze NFT market trends using RStudio and statistical methods
- Quantify public interest patterns using Google Trends data
- Identify and measure correlations between NFTs and cryptocurrency
- Explore temporal patterns and market seasonality
- Provide insights for future market forecasting

## Key Findings

| Finding | Details |
|---------|---------|
| **Correlation** | Strong positive correlation detected between NFT and cryptocurrency search interest |
| **Data Limitation** | Current dataset size restricts reliable predictive modeling |
| **Trends** | Seasonal patterns and adoption cycles identified |
| **Volatility** | Market shows significant interest fluctuations over time |

## Project Structure

```
yohernan/NFTs/
├── Final_Project_NFTs.Rmd           # Main analysis and methodology
├── Final_Project_NFTs.nb.html       # Interactive HTML notebook (analysis)
├── FinalPresentation.Rmd            # Presentation slides
├── FinalPresentation.html           # HTML presentation output
├── README.md                        # This file
└── .gitignore                       # Git ignore rules
```

## Tech Stack

| Tool | Purpose |
|------|---------|
| **R** | Statistical analysis & data processing |
| **RStudio** | IDE for R development |
| **tidyverse** | Data manipulation & visualization |
| **gtrendsR** | Google Trends data extraction |
| **ggplot2** | Advanced data visualization |
| **R Markdown** | Dynamic document generation |

## Data Sources

- **Google Trends API** - Search interest data for NFTs and cryptocurrency
- **Time Period**: Historical search trends from gtrendsR
- **Resolution**: Weekly/monthly aggregated interest metrics

## Quick Start

### Prerequisites
- R (version 3.6+)
- RStudio (optional but recommended)
- Required packages: `tidyverse`, `gtrendsR`, `ggplot2`

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yohernan/NFTs.git
   cd NFTs
   ```

2. **Install dependencies**
   ```r
   install.packages(c("tidyverse", "gtrendsR", "ggplot2"))
   ```

3. **Open the analysis**
   - In RStudio: Open `Final_Project_NFTs.Rmd`
   - Or: Open `Final_Project_NFTs.nb.html` in your web browser for interactive view

### Running the Analysis

```r
# In RStudio, click "Knit" or run:
rmarkdown::render("Final_Project_NFTs.Rmd")
```

## Documentation

- **Main Analysis**: See `Final_Project_NFTs.Rmd` for detailed methodology and code
- **Interactive Results**: Open `Final_Project_NFTs.nb.html` to view analysis with outputs
- **Presentation**: View `FinalPresentation.html` for key takeaways

## Methodology

### Approach
1. **Data Collection** - Extract Google Trends data for NFTs and cryptocurrency
2. **Data Cleaning** - Process and normalize search interest metrics
3. **Exploratory Analysis** - Visualize trends and patterns
4. **Statistical Testing** - Calculate correlations and test significance
5. **Visualization** - Create meaningful charts and graphs

### Statistical Methods
- Pearson correlation analysis
- Time series decomposition
- Trend analysis
- Seasonal decomposition (if applicable)

## Key Visualizations

The project includes:
- Trend lines showing NFT interest over time
- Cryptocurrency correlation plots
- Seasonal pattern analysis
- Comparative market interest graphs

## Related Resources

- [Google Trends](https://trends.google.com/)
- [gtrendsR Documentation](https://github.com/PMassicotte/gtrendsR)
- [R Markdown Guide](https://rmarkdown.rstudio.com/)
- [tidyverse](https://www.tidyverse.org/)


- GitHub: https://github.com/yohernan
- Project: NFT Market Analysis

