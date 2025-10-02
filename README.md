# Total_Water_Storage_Anomaly_TWSA
Comprehensive Analysis: Finland Water Storage Trends (2002-2024)

## Author: Mostafa Saghafi
## Colab link: https://colab.research.google.com/drive/1O3aNvpmv604qVNvMboXG_Kpq3F5ulQko?usp=sharing


# Finland Total Water Storage Anomaly (TWSA) Analysis Report

## Executive Summary

This report presents an analysis of Total Water Storage Anomaly (TWSA) in Finland from 2002 to 2024. The analysis reveals that Finland is experiencing a significant positive trend in water storage, gaining approximately 1.24 gigatons of water annually. This trend represents a critical insight into Finland's changing hydrological conditions, with notable extreme years identified in 2002, 2003 (extremely dry), and 2024 (extremely wet). The findings highlight important shifts in Finland's water resources that have implications for water management, ecosystem health, and climate adaptation strategies.

## Introduction

Total Water Storage Anomaly (TWSA) represents the deviation of the total amount of water stored in a region from a long-term average. This includes surface water (lakes, rivers), soil moisture, groundwater, snow, and ice. TWSA measurements provide valuable information about hydrological changes and are increasingly important for monitoring climate change impacts on water resources.

## Methodology

This analysis utilized time series data of TWSA measurements over Finland spanning from 2002 to 2024. A linear regression model was applied to determine the trend in water storage changes over time. Statistical analysis was performed to identify extreme years and seasonal patterns. Water volume changes were converted to mass (gigatons) to quantify the annual water gain or loss across Finland's territory.

## Results and Analysis

### Linear Regression Results

Table 1 presents the key statistical parameters from the linear regression analysis of TWSA data.

**Table 1: Linear Regression Statistical Parameters**

| Parameter | Value | Units |
|-----------|-------|-------|
| Slope | 0.00102308 | cm/day |
| Intercept | -3.1739 | cm |
| R-squared | 0.2259 | - |
| P-value | 8.106437e-15 | - |
| Standard Error | 0.00012327 | cm/day |

### Water Storage Change

The linear regression results translate to significant annual water storage changes in Finland, as summarized in Table 2.

**Table 2: Annual Water Storage Change in Finland**

| Parameter | Value | Units |
|-----------|-------|-------|
| Rate | +0.3737 | cm/year |
| Volume change | +1.24 × 10^9 | cubic meters/year |
| Mass change | +1.2415 | gigatons/year |
| Status | **GAINING** | - |

### Long-Term Trend in Water Storage

![Total Water Storage Anomaly (TWSA) in Finland (2002-2023)](Third figure showing trend line)

The scatter plot with trend line demonstrates the positive trend in monthly TWSA values over the study period. The red line represents the linear trend with a slope of 0.374 cm/year (1.242 Gt/year). Despite considerable monthly variability, the overall upward trend is statistically significant.

### Distribution of TWSA Values

![Distribution of TWSA Values](First figure, left panel)

The histogram shows the frequency distribution of all TWSA measurements across the study period. The data follows a roughly normal distribution with:
- Mean value: 0.96 cm
- Median value: 0.61 cm

The slight positive skew indicates that positive anomalies (wetter conditions) tend to be more extreme than negative anomalies (drier conditions).

### Annual TWSA Distribution

![Annual TWSA Distribution](First figure, right panel)

The box plot illustrates the distribution of TWSA values for each year from 2002 to 2024. This visualization effectively shows:
- The progression from predominantly negative anomalies in the early 2000s to increasingly positive anomalies in recent years
- The interannual variability in water storage
- The extreme dry years (2002-2003) and wet years (particularly 2024)
- The increasing median values over time, consistent with the positive trend

### Annual Statistics

Table 3 provides detailed statistics for each year in the study period.

**Table 3: Annual TWSA Statistics (2002-2024)**

| Year | Mean TWSA (cm) | Min TWSA (cm) | Max TWSA (cm) | Std Dev (cm) | Sample Count | Z-score |
|------|---------------|--------------|--------------|-------------|--------------|---------|
| 2002 | -8.078845 | -12.774193 | 0.055535 | 4.709453 | 8 | -2.379395 |
| 2003 | -5.875520 | -12.108413 | 0.994061 | 3.516977 | 11 | -1.794842 |
| 2004 | 0.233297 | -3.946094 | 8.196609 | 3.424759 | 12 | -0.174144 |
| 2005 | 0.362718 | -5.893318 | 8.170953 | 3.612083 | 12 | -0.139808 |
| 2006 | -3.403026 | -12.152193 | 6.336295 | 6.056175 | 12 | -1.138878 |
| 2007 | 0.855826 | -3.858342 | 4.787235 | 3.093847 | 12 | -0.008984 |
| 2008 | 2.197574 | -3.323671 | 8.047807 | 4.106038 | 12 | 0.346988 |
| 2009 | -0.395350 | -5.263106 | 4.011717 | 2.923921 | 12 | -0.340927 |
| 2010 | -1.955706 | -5.610892 | 2.926909 | 3.126836 | 11 | -0.754897 |
| 2011 | 2.025323 | -4.723881 | 8.841202 | 4.418276 | 11 | 0.301289 |
| 2012 | 3.665656 | -0.402035 | 8.663173 | 3.024232 | 10 | 0.736477 |
| 2013 | 0.210891 | -7.502654 | 5.056659 | 4.810840 | 9 | -0.180088 |
| 2014 | -1.684189 | -6.497492 | 4.327534 | 3.715379 | 8 | -0.682862 |
| 2015 | 3.766401 | -2.832237 | 9.927838 | 3.807874 | 9 | 0.763206 |
| 2016 | 0.251773 | -4.892674 | 5.693908 | 3.541476 | 9 | -0.169242 |
| 2017 | 5.153008 | -0.026067 | 9.122780 | 3.462423 | 5 | 1.131079 |
| 2018 | -2.608256 | -5.448954 | -0.490465 | 1.851524 | 6 | -0.928021 |
| 2019 | -0.155078 | -7.001589 | 8.990013 | 4.980491 | 12 | -0.277182 |
| 2020 | 5.437322 | -1.110934 | 15.386979 | 5.997484 | 12 | 1.206509 |
| 2021 | 3.216047 | -2.866744 | 8.724628 | 3.766872 | 12 | 0.617194 |
| 2022 | 4.943202 | -3.435083 | 12.375948 | 5.136570 | 12 | 1.075417 |
| 2023 | 5.246705 | -1.740358 | 10.678953 | 3.771680 | 12 | 1.155937 |
| 2024 | 7.053064 | 1.946551 | 15.118986 | 4.380347 | 9 | 1.635173 |

### Extreme and Record Years

![Annual Mean TWSA (Extreme Years Highlighted)](Third figure, bottom panel)

The bar chart highlights years with extreme TWSA values. Table 4 summarizes the extreme years identified in the analysis.

**Table 4: Extreme Years (z-score > 1.5 or < -1.5)**

| Year | Condition | Mean TWSA (cm) | Z-score | Standard Deviation (cm) |
|------|-----------|----------------|---------|-------------------------|
| 2002 | EXTREMELY DRY | -8.08 | -2.38 | 4.71 |
| 2003 | EXTREMELY DRY | -5.88 | -1.79 | 3.52 |
| 2024 | EXTREMELY WET | 7.05 | 1.64 | 4.38 |

**Table 5: Record Years**

| Condition | Year | Mean TWSA (cm) |
|-----------|------|----------------|
| Wettest Year | 2024 | 7.05 |
| Driest Year | 2002 | -8.08 |
| Difference | | 15.13 |

The difference between the wettest year (2024) and the driest year (2002) is 15.13 cm of water equivalent thickness, representing a dramatic shift in water storage conditions over the study period.

### Seasonal Pattern

![Seasonal Pattern of TWSA in Finland](Fourth figure)

The bar chart illustrates the seasonal cycle of water storage in Finland, with key seasonal characteristics summarized in Table 6:

**Table 6: Seasonal Pattern Highlights**

| Season | Months | TWSA Condition | Notable Values |
|--------|--------|----------------|----------------|
| Winter-Spring | January-March | Highest positive anomalies | Peak in March: 5.42 cm |
| Summer | June-September | Lowest values | Minimum in July: -2.99 cm |
| Autumn | October-December | Recovery period | Gradually increasing values |

This pattern aligns with Finland's hydrological cycle, where snow accumulation during winter, spring melt, summer evapotranspiration, and autumn precipitation play key roles in water storage dynamics.

### Data Quality Summary

**Table 7: Data Quality Metrics**

| Metric | Value | Notes |
|--------|-------|-------|
| Total observations | 238 | Monthly data points |
| Time span | 22.5 | years |
| Regression R² | 0.2259 | Trend explains 22.6% of variance |

## Discussion

### Climate Change Implications

The observed trend of increasing water storage (+1.24 Gt/year) may reflect several aspects of climate change in Finland:

1. **Increased Precipitation**: Climate models predict higher precipitation in northern Europe under warming scenarios, which could contribute to the observed water storage gains.

2. **Changes in Seasonal Patterns**: While total water is increasing, the seasonal distribution may be shifting, potentially affecting ecosystems and water resource management.

3. **Contrast with Global Trends**: The positive trend in Finland contrasts with water loss trends observed in many other regions globally, highlighting the spatial heterogeneity of climate change impacts.

### Hydrological Cycle Changes

The dramatic shift from extremely dry conditions in 2002-2003 to extremely wet conditions in 2024 suggests potential intensification of hydrological extremes. This pattern is consistent with climate change projections that indicate more variable precipitation and intensified hydrological cycles.

### Data Considerations

The R-squared value of 0.2259 indicates that while the trend is statistically significant, approximately 77% of the variance in TWSA is explained by factors other than the linear trend. This suggests complex interactions between climate oscillations, land use changes, and other environmental factors.

## Conclusion

This analysis demonstrates that Finland is experiencing a significant increase in total water storage at a rate of approximately 1.24 gigatons per year. The transition from record dry conditions in the early 2000s to record wet conditions in recent years represents a substantial shift in Finland's hydrology.

These findings have important implications for:

1. **Water Management**: Infrastructure planning may need to account for increasing water availability and potential flooding risks.

2. **Ecosystem Management**: Changes in water availability will affect forest health, wetland ecosystems, and aquatic habitats.

3. **Climate Adaptation**: Understanding these trends is essential for developing appropriate climate adaptation strategies.

Further research is recommended to investigate the specific drivers of this trend, regional variations within Finland, and projections for future changes in water storage under different climate scenarios.

## Summary of Key Findings

**Table 8: Summary of Key Results**

| Finding | Value | Units |
|---------|-------|-------|
| Annual water gain | 1.2415 | gigatons/year |
| Rate of TWSA change | 0.3737 | cm/year |
| Mean TWSA (2002-2024) | 0.96 | cm |
| Median TWSA | 0.61 | cm |
| Wettest year | 2024 (7.05 cm) | - |
| Driest year | 2002 (-8.08 cm) | - |
| Extreme wet-dry difference | 15.13 | cm |
| Highest monthly TWSA | March (5.42 cm) | - |
| Lowest monthly TWSA | July (-2.99 cm) | - |
