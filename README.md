# **Wine Quality Analysis**

## Introduction
A wine quality dataset was used to provide the framework for our project. The dataset contains information about red and white Vinho Verde wine samples from Northern Portugal. The data models the quality of wine based on physiochemical tests.

This analysis focused on leveraging the fundamental elements provided within the dataset and presenting them to potential winemakers. A thorough investigation was conducted into the factors contributing to high-quality wine and developed visualizations to illustrate these findings. Gaining insights into these factors has equipped us with the fundamental knowledge to provide insights into high-quality wine.

## Factors Analyzed
The following factors focused on: fixed acidity, volatile acidity, citric acid, sulphates, chlorides, residual sugar, pH, and alcohol.

The analysis focused on the acidity contents of wine since acids contribute to the overall taste. Acidity in wine has a strong relationship to pH, stability, and color. 

### Fixed Acidity
- Average: 7.22
- Range: 3.8 to 15.9
- Description:
This refers to tartaric acid, the primary acid in wine. It contributes to the wine's sourness and is influenced by the climate and soil content where the grapes are grown. Higher fixed acidity levels help maintain a wine’s freshness and structural integrity.

### Volatile Acidity
- Mean: 0.34
- Range: 0.08 to 1.58
- Description:
Measures gaseous acids impacting taste, spoilage, and aroma of the wine. High levels of volatile acid can lead to vinegar-like flavours and aromas. The high levels of volatile acidity are from unhealthy grapes, poor winery hygiene, and oxidative processes. Thus, there is a negative correlation between the values.

### Citric Acid
- Mean: 0.32
- Range: 0 to 1.66
- Description:
Adds freshness and flavor complexity. Citric acid is derived from wine grapes and can be produced in fermentation. Higher citric acid levels are positively associated with higher wine quality ratings.


### Sulphates
- Mean: 0.53
- Range: 0.22 to 2.0
- Description:
Sulphates act as antimicrobials and antioxidants. They help preserve the wine by preventing oxidation and spoilage, which are critical for maintaining the quality over time. Higher sulphate levels are often associated with better-quality wine.

### Chlorides
- Mean: 0.056
- Range: 0.009 to 0.611
- Description:
Primarily come from the soil and water used in vineyards, and any salt-based treatments used in the winemaking processes.​ In high-quality wines, chloride levels are low to balance taste.

### Residual Sugar
- Average: 5.44
- Range: 0.6 to 65.8
- Description:
Residual sugar is from the naturally occurring sugars after the fermentation process. The less sugar, the drier the wine. In white wines, the sugar content decreases with the quality of wine. In red wine, the sugar level stays consistent regardless of the quality. This residual sugar is measured in grams per liter (g/L). Dry wines have less sugar and are generally better quality than the cheaper wines, which are very high in sugar content. However, the sugar content can also vary based on the type of wine. For example, a high-quality White Zinfandel (7.5g/liter) will have more residual sugar in comparison to a Sauvignon Blanc which is considered a Dry Wine with 3.75g/L residual sugar. For red wine, the sugar level stays consistent regardless of the quality as seen in the graph. That is because the fermentation process and grapes are different than white wine. While making red wine the whole grape is used, compared to when making white wine, only juice from the grapes is used during the fermentation process. There is also less sugar the longer the wine is fermented. Red wine has two fermentation processes while white has one.

### pH
- Average: 3.22
- Range: 2.72 to 4.01
- Description:
Grapes make wine acidic. For a wine to have the complexity of flavors and composition that it does, it must have a pH between 3 and 4. The pH determines the body of the wine, along with the alcohol content, which correlates to the overall quality of the wine. Concerning our graphs, the quality of wine is on a scale between 3 to 9. Where 3 is the lowest and 9 is the highest quality.  Red wines have higher acidities and improve with time, while low-acidity wines are less stable and more susceptible to microbes. When understanding the body of the wine, red and white wines can be divided into light-bodied, medium-bodied, and full-bodied wines. Full-bodied wines are generally depicted as higher quality wines, while light-bodied are lower quality as shown below. Lower-bodied wines have a higher pH and lower alcohol content, while high-bodied wines have lower acidity and higher alcohol content.

### Alcohol
- Average: 10.49%
- Range: 8.0% to 14.9%
- Description:
Contributes to the wine’s body and overall quality. The higher alcohol content is generally associated with higher-quality wines.
Red wines tend to have higher alcohol content compared to white wines. 

## Results and Conclusions
High-quality wine typically exhibits a well-balanced combination of acidity, alcohol, and residual sugar. Fixed acidity and citric acid are crucial for wine's structure and freshness, while sulphates and sulfur dioxide help maintain stability and prevent spoilage.

![Red Wine Components Contribution by Percentages](red_wine_components_percentages.png)

![White Wine Components Contribution by Percentages](white_wine_components_percentages1.png)

### Future Research

- Analyze the impact of different grape varieties based on wine quality.
- Explore how different climates around the world impact the fixed acidity in wine.
- Investigate the effects of aging on various wine attributes.
- Research the financial information on the different wine types.
- Explore the physiochemical makeup of specific types of wines, for example; White Zinfandel, Sauvignon Blanc, Cabernet Sauvignon, and Pinot Noir.

### Google Slide Presentation (https://docs.google.com/presentation/d/1sQnuULPuMsbjpVWxsrCdEkvHKYzUZbi5cg-QlzIyACE/edit?usp=sharing)

## References
1. UCI Machine Learning Repository. (2009). Wine Quality Dataset. Retrieved from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality).
2. Wine Folly. (n.d.). Wine Acidity: The Science and Magic. Retrieved from [Wine Folly](https://winefolly.com/tutorial/wine-acidity/).
3. Waterhouse Lab. (n.d.). Fixed Acidity in Wine. Retrieved from [Waterhouse Lab](https://waterhouse.ucdavis.edu/whats-in-wine/fixed-acidity).
4. Wine Spectator. (n.d.). Residual Sugar in Wine. Retrieved from [Wine Spectator](https://www.winespectator.com/articles/residual-sugar-in-wine).
5. Wine Enthusiast. (n.d.). Understanding Wine Sweetness. Retrieved from [Wine Enthusiast](https://www.winemag.com/2018/05/16/wine-sweetness-chart/).
6. WineMakerMag. (n.d.). The Role of Sulphites in Wine. Retrieved from [WineMakerMag](https://winemakermag.com/article/858-the-role-of-sulfites-in-wine).
7. SpringerLink. (2009). Using Data Mining for Wine Quality Assessment. Retrieved from [SpringerLink](https://link.springer.com/chapter/10.1007/978-1-84800-370-3_16).
8. RStudio Pubs. (n.d.). Quantifying Quality of Red Wine: The Predictive Powers of pH and Sulphate Content. Retrieved from [RStudio Pubs](https://rpubs.com/).
