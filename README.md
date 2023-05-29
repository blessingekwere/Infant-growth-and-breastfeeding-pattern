# Infant-growth-and-breastfeeding-pattern

## Introduction
![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/GettyImages%201210806663%201280x853.jpg)
###### Photo Source: Google

 Breastfeeding is the act of providing a baby with breast milk directly from the mother's breast. It is a natural and essential process that plays a crucial role in the growth and development of babies. Breastfeeding is the recommended method of infant feeding as it provides numerous benefits for both the baby and the mother. Breast milk is a complete source of nutrition for infants, containing a perfect balance of carbohydrates, proteins, and fats, along with vitamins, minerals, and antibodies that help protect against infections and diseases.

The purpose of breastfeeding is to nourish and support the optimal growth and development of babies. Breast milk is easily digestible, promotes the development of a healthy immune system, and provides protection against various illnesses. It is also known to reduce the risk of certain conditions like allergies, asthma, obesity, and diabetes in infants. Breastfeeding not only fulfills a baby's nutritional needs but also promotes bonding and emotional connection between the mother and the baby. Skin-to-skin contact during breastfeeding releases hormones that create a sense of closeness and comfort, fostering a strong mother-infant relationship. The act of breastfeeding stimulates the baby's oral motor skills, jaw development, and facial muscles, promoting the proper development of the baby's mouth and teeth. It also helps in the development of hand-eye coordination and facilitates the growth of the baby's palate and facial bones.

![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Tracking%20growth%202.jpg)
###### Photo Source: Google

## Problem Statement

Breastfeeding is the best way to feed a baby. It provides the baby with all the nutrients it needs, and it also has many health benefits for both the mother and the baby. However, not all mothers are able to breastfeed for the recommended amount of time. There are many factors that can contribute to this, such as work, lack of support, and medical conditions.

This project aims to use data to investigate the relationship between breastfeeding patterns and the growth patterns of babies. The project will utilize statistical methods to analyze the data and identify any correlations between breastfeeding patterns and growth patterns.

The objective of this project is to utilize the findings to aid mothers in making well-informed decisions regarding breastfeeding. Furthermore, the project aims to provide healthcare providers with valuable insights on how to support breastfeeding mothers. The project addresses the following research questions:

* Are there any correlations between breastfeeding patterns and height?
* Are there any associations between breastfeeding patterns and weight?
* Is there a correlation between the height and weight of individuals?
* How does the distribution of height and weight vary across different months?
* What are the average height and weight of individuals by age, considering their breastfeeding patterns?
* How do height and weight differ among various breastfeeding patterns?

Please note that these revisions aim to improve the clarity and conciseness of the original statement while maintaining the intent and meaning of the research questions.

By exploring and analyzing the provided dataset, this project aims to gain insights into the impact of breastfeeding patterns on the growth patterns of babies. The findings will contribute to a better understanding of the importance of breastfeeding and assist in providing evidence-based recommendations for healthcare professionals and parents regarding breastfeeding practices and their effects on infant growth and development.

![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/images%20(2).jpg)
###### Photo Source: Google

## Data Sourcing
The data used in this project was collected from Braithwaite Memorial Specialist Hospital in Port Harcourt, Rivers State, Nigeria in 2015. The dataset contains information on four ways of breastfeeding babies, including Exclusive Breastfeeding, Breastfeeding with Water, Partial Breastfeeding, and No Breastfeeding.

A total of 120 babies were included in the dataset, with 30 babies selected for each feeding method. The height and weight of each baby were measured from their first to sixth months. The dataset consists of 720 rows and 5 columns including 
* S/N- Serial Number of rows
* Weight- Weight of the baby
* Height – Height of the baby
* Month – Age of the baby (in months)
* Breastfeeding pattern- Ways of breastfeeding babies

Find the link to the dataset [here](https://www.kaggle.com/datasets/chidirolex/weightheight-and-breastfeeding-pattern-of-infants?resource=download)

## Tool Used
The tool used for this project is PowerBI

## Skills Demonstrated
The analysis of infant growth and breastfeeding patterns using Power BI demonstrates several skills and capabilities. Here are the key skills demonstrated in this analysis:
* Data Transformation
* Data Visualization
* Insight Generation
* Contextual Interpretation
* Reporting and Dashboard Creation

## Data cleaning
The dataset was not quite messy, hence there was just little cleaning that was to be carried out to ensure that the data is fit for further analysis. Some of the steps taken during data cleaning and transformation were:

* Formatting all the columns to their proper data type
* Splitting the month column using space as a delimeter to ensure that I have a column with just the number of month as the age and then I renamed the new column as age(month) and then I removed the column that just had months.
![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Screenshot%20(100).png)
##### Month column before splitting

![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Screenshot%20(101).png)
##### Splitting Month column using space as delimeter

* Correction of the misspellings
* Ensuring that the various columns that had continuous data that is the height and weight columns were formatted in the most common unit of measurements that is kilograms and centimeters. Looking at the height column, I noticed that the height column was in inches (though not indicated), so I had to convert it to centimeters(cm) using the custom column command. To convert the entire column to centimeters, I multiplied the entire column by 2.54 and rounded it up to 2 decimal places.
![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Screenshot%20(102).png)

After the conversion, I compared the values I had for the height to the values I have on this [site](https://www.babycenter.com/baby/baby-development/average-weight-and-growth-chart-for-babies-toddlers-and-beyo_10357633), which served as a guide showing the ranges of heights and weights of babies by months to be sure I was on the right track. 

## ANALYSIS
### Average height by month
* To visualize the average height of babies at different months, a line chart was created. The chart displays the average height (in centimeters) on the y-axis and the corresponding months on the x-axis.The line chart clearly illustrates the progression of height development during the first six months of a baby's life. The average height at 1 month was 46.49 cm, which increased to 48.87 cm at 2 months, showing a noticeable growth. At 3 months, the average height further increased to 51.27 cm. The growth rate continued, reaching 53.24 cm at 4 months and 55.27 cm at 5 months. Finally, at 6 months, the average height peaked at 57.31 cm.

![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Height%20by%20Month.png)

The line chart effectively demonstrates the growth pattern, with each point representing the average height for a specific month. The gradual increase in height over time indicates the natural progression of growth during the early months of a baby's life.

### Average weight by month
*	To visualize the average weight of babies at different months, a line chart was created. The chart displays the average weight (in kilograms) on the y-axis and the corresponding months on the x-axis.

The line chart clearly illustrates the progression of weight development during the first six months of a baby's life. The average weight at 1 month was 4.60 kg, which increased to 5.46 kg at 2 months, showing a noticeable growth. At 3 months, the average weight further increased to 5.94 kg. The growth rate continued, reaching 6.31 kg at 4 months and 6.72 kg at 5 months. Finally, at 6 months, the average weight peaked at 7.22 kg.

![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Weight%20by%20Month.png)

The line chart effectively demonstrates the growth pattern, with each point representing the average weight for a specific month. The gradual increase in weight over time indicates the natural progression of growth during the early months of a baby's life.

###	Relationship between height and weight
* The scatter plot visualizing the height and weight of babies reveals a correlation coefficient of 0.189388901. This coefficient suggests a weak positive correlation between height and weight. Although the correlation is positive, the coefficient value indicates that the relationship between height and weight is not particularly strong. It implies that while there may be some tendency for taller babies to have higher weights, the correlation is not significant enough to make definitive conclusions.

![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Relationship%20between%20height%20and%20weight.png)

It is important to note that correlation does not imply causation, and other factors may contribute to the observed variations in height and weight. Further analysis and consideration of additional variables or factors would be beneficial to gain a more comprehensive understanding of the relationship between height and weight in babies.

### Average weight by breastfeeding pattern
![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Average%20weight%20by%20breastfeeding%20pattern.png)

From the analysis of the impact of breastfeeding patterns on weight using a bar chart, the following insights can be derived:

* Average Weight for Breastfeeding and Water (6.35kg): This indicates the highest average weight among the breastfeeding patterns considered. It suggests that babies who receive a combination of breastfeeding and water tend to have a slightly higher weight compared to other patterns.

* Average Weight for Exclusive Breastfed Babies (6.26kg): Exclusive breastfeeding shows a slightly lower average weight compared to the breastfeeding and water pattern. This suggests that the introduction of water alongside breastfeeding may contribute to a slight increase in weight.

* Average Weight for Partial Breastfed Babies (6.17kg): The average weight for partial breastfed babies is lower than both the breastfeeding and water pattern and exclusive breastfed babies. This indicates that introducing non-breast milk components, such as formula or solid foods, alongside breastfeeding may have a modest impact on weight reduction.

* Average Weight for Babies Not Breastfed (5.39kg): This shows the lowest average weight among the breastfeeding patterns analyzed. It suggests that not breastfeeding and relying solely on non-breast milk alternatives, such as formula feeding, may lead to a significant reduction in weight compared to breastfeeding patterns.

#### Percentage Increase and Reduction:
* The breastfeeding and water pattern shows a 0.9% increase in weight compared to exclusive breastfed babies. This slight increase may be attributed to the additional intake of water, which contributes to a slightly higher weight gain.
* Exclusive breastfed babies exhibit a 2.8% reduction in weight compared to the breastfeeding and water pattern. This reduction might be due to the absence of water intake and a focus solely on breast milk, which could lead to slightly lower weight gain.
* Partial breastfed babies experience a 1.4% reduction in weight compared to exclusive breastfed babies. This reduction may be associated with the introduction of non-breast milk components, which could contribute to a slight decrease in weight.
* Babies not breastfed show a substantial 14.8% reduction in weight compared to the breastfeeding and water pattern. The absence of breast milk, which provides optimal nutrition and nourishment, may explain this significant weight reduction.

* Possible Reasons:
The variations in weight between different breastfeeding patterns can be influenced by several factors, including:

#### Nutritional Composition: Breast milk is uniquely tailored to meet the nutritional needs of infants. The introduction of water, formula, or solid foods alongside breastfeeding may alter the overall nutrient intake, leading to different weight outcomes.

#### Feeding Practices: The frequency, duration, and methods of breastfeeding can impact weight gain. Patterns with higher breastfeeding frequency or longer duration may contribute to greater weight due to increased milk intake.

#### Satiety and Caloric Intake: Breast milk provides optimal satiety and regulates calorie intake. Introducing non-breast milk alternatives or not breastfeeding may affect satiety cues and result in variations in calorie consumption, potentially leading to different weight outcomes.

#### Individual Variances: Each baby is unique, and factors such as metabolism, genetics, and growth patterns can contribute to weight variations among breastfeeding patterns.

### Average height by breastfeeding pattern
![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Average%20height%20by%20breastfeeding%20pattern.png)

The analysis of the impact of breastfeeding pattern on height, visualized through a line chart, provides insights into the average height based on different breastfeeding patterns. Here are the insights derived from the given data:

* Average height for babies not breastfed (56.35 cm): The chart shows that babies who were not breastfed have the highest average height among the listed patterns. This suggests a potential correlation between not being breastfed and higher height. Possible reasons for this observation could include genetic factors, nutrition from alternative sources (such as formula), or other environmental factors.

* Average height for babies breastfed with water (51.3 cm): The  chart indicates that babies who were breastfed with water have a lower average height compared to the other breastfeeding patterns. Breastfeeding with water alone may not provide the same nutritional benefits as breastfeeding with breast milk. Inadequate nutrition or reduced intake of breast milk could be potential reasons for the lower average height in this group.

* Average height for exclusively breastfed babies (50.86 cm): The chart shows a slightly lower average height for exclusively breastfed babies compared to those not breastfed and those breastfed with water. It's important to note that this analysis does not consider the duration of exclusive breastfeeding, which could impact the results. However, factors such as genetics, overall nutrition, and individual growth rates can influence the observed average height.

* Average height for partially breastfed babies (49.97 cm): The chart displays the lowest average height among the listed breastfeeding patterns for partially breastfed babies. This pattern may suggest that a combination of breastfeeding and other sources of nutrition (such as formula or solid foods) may have an impact on the overall height of the babies. Factors like varied nutritional intake and feeding practices could contribute to the observed average height in this group.

*It's important to note that height is influenced by various factors, including genetics, overall nutrition, individual growth patterns, and environmental factors. Breastfeeding patterns alone may not solely determine the height of babies. Consideration of other variables, such as socioeconomic factors, dietary habits, and genetic predispositions, would provide a more comprehensive understanding of the relationship between breastfeeding patterns and height in babies.
To gain a more comprehensive understanding of the relationship between breastfeeding patterns and height, it would be beneficial to analyze a larger sample size and consider additional factors such as duration of breastfeeding, overall nutrition, and other relevant variables that could impact height development in babies.*

### Average height and weight by breastfeeding pattern for ages 1-3 month
![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Average%20weight%20and%20height%201-3%20months.png)
#### Height Comparison

* Exclusive Breastfed Babies (47.67cm): The visual indicates that babies who are exclusively breastfed have an average height of 47.67cm. This shows that exclusive breastfeeding during the 1-3 month period is associated with this height range.

* Babies Breastfed with Water (48.06cm): The chart reveals that babies who are breastfed with water have a slightly higher average height of 48.06cm compared to exclusively breastfed babies. This suggests that the inclusion of water in the breastfeeding pattern may have a slight positive impact on height during this period.

* Babies Breastfed Partially (47.34cm): The analysis shows that babies who are breastfed partially have a slightly lower average height of 47.34cm compared to exclusively breastfed babies. This indicates that partial breastfeeding may have a minimal impact on height during the 1-3 month period.

* Babies Not Breastfed (52.44cm): The visual demonstrates that babies who are not breastfed have a significantly higher average height of 52.44cm compared to the other breastfeeding patterns. This suggests a potential correlation between not being breastfed and a higher average height during this age range.

#### Weight Comparison

* Exclusive Breastfed Babies (5.66kg): The chart indicates that babies who are exclusively breastfed have an average weight of 5.66kg during the 1-3 month period. This weight range is associated with exclusive breastfeeding.

* Babies Breastfed with Water (5.42kg): The analysis reveals that babies who are breastfed with water have a slightly lower average weight of 5.42kg compared to exclusively breastfed babies. This suggests that the inclusion of water in the breastfeeding pattern may have a slight impact on weight during this period.

* Babies Breastfed Partially (5.27kg): The visual shows that babies who are breastfed partially have a slightly lower average weight of 5.27kg compared to exclusively breastfed babies. This indicates that partial breastfeeding may have a minimal impact on weight during the 1-3 month period.

* Babies Not Breastfed (4.98kg): The chart demonstrates that babies who are not breastfed have a lower average weight of 4.98kg compared to the other breastfeeding patterns. This suggests a potential correlation between not being breastfed and a lower average weight during this age range.

### Average height and weight by breastfeeding pattern for ages 4-6 month
![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/Average%20height%20and%20weight%204-6%20month.png)

From the analysis of the impact of breastfeeding pattern on the height and weight of individuals using a 100% stacked bar chart in Power BI for the 4-6 month age range, the following insights can be derived:

#### Height Comparison

* Exclusive Breastfed Babies (54.05cm): The visual indicates that exclusive breastfed babies have a slightly lower average height compared to babies breastfed with water (54.20cm) and babies breastfed partially (52.60cm). The difference in height between the three breastfeeding patterns is relatively small, suggesting that the choice of breastfeeding pattern may have a limited impact on height during this age range. Babies Not Breastfed (60.25cm): The chart reveals that babies who were not breastfed have a significantly higher average height compared to the other breastfeeding patterns. This indicates a potential correlation between not being breastfed and a higher average height at this stage of development.

#### Weight Comparison

* Exclusive Breastfed Babies (6.86kg): The visual shows that exclusive breastfed babies have a slightly lower average weight compared to babies breastfed with water (7.28kg) and babies breastfed partially (7.07kg). The difference in weight between the three breastfeeding patterns is not substantial, suggesting that the choice of breastfeeding pattern may have a limited impact on weight during this age range.
* Babies Not Breastfed (5.79kg): The chart indicates that babies who were not breastfed have a lower average weight compared to the other breastfeeding patterns. This suggests a potential correlation between not being breastfed and a lower average weight at this stage of development.

*It's important to note that these insights are based on the specific data provided for the 4-6 month age range. The analysis should be interpreted in the context of the given dataset and the limitations of the data. Other factors, such as genetics, overall nutrition, and individual growth rates, can also contribute to variations in height and weight. To draw more robust conclusions, it would be beneficial to analyze data across different age groups and consider additional variables like socioeconomic factors, dietary habits, and individual health conditions.*

### Dashboard
Below is the infant growth and breastfeeding pattern dashboard. Feel free to interact with the dashboard [here](https://app.powerbi.com/groups/me/reports/f9940b6e-4335-414e-a1db-be558e0fa783/ReportSection?experience=power-bi)

![](https://github.com/blessingekwere/Infant-growth-and-breastfeeding-pattern/blob/main/breastfeeding%20pattern_page-0001.jpg)
##### Infant growth and breastfeeding pattern dashboard

### Recommendation
Based on the insights derived from the analysis of the impact of breastfeeding patterns on height and weight, the following recommendations can be made for the infant and breastfeeding pattern dataset:

* Height Development Recommendations

Encourage exclusive breastfeeding: Although exclusive breastfeeding showed a slightly lower average height compared to other breastfeeding patterns, it provides essential nutrition for infants. Encouraging exclusive breastfeeding for the first 4-6 months of a baby's life can support healthy growth and development.
Monitor height of non-breastfed babies: The analysis indicates that babies not breastfed had a significantly higher average height. Healthcare professionals should closely monitor the growth and development of non-breastfed babies to ensure they are receiving adequate nutrition and support their overall well-being.

* Weight Development Recommendations

Promote exclusive breastfeeding with water supplementation: Babies breastfed with water showed a slightly higher average weight compared to exclusive breastfed babies. Promoting exclusive breastfeeding while introducing small amounts of water as recommended by healthcare professionals can contribute to healthy weight gain during this age range.

* Educate on the potential impacts of partial breastfeeding: Partial breastfed babies had a slightly lower average weight compared to both exclusive breastfed babies and babies breastfed with water. Educating parents about the potential impact of introducing non-breast milk components (formula or solid foods) alongside breastfeeding may help them make informed decisions regarding their baby's weight development

* Provide support for non-breastfed babies: Babies not breastfed showed a lower average weight. Providing appropriate support and guidance to parents who choose not to breastfeed, such as ensuring access to quality formula feeding and monitoring weight gain, can help promote healthy growth and development.

* Correlation between Height and Weight Recommendations

Consider multiple factors: The analysis showed a weak positive correlation between height and weight in babies. It's important to consider multiple factors, such as genetics, overall nutrition, and individual growth patterns, when assessing height and weight development. A holistic approach that considers various aspects of a baby's health and well-being will provide a more comprehensive understanding.

* Further analysis and research

Expand the dataset: To strengthen the recommendations and draw more robust conclusions, expanding the dataset with a larger sample size and diverse demographics would be valuable. This would allow for more accurate insights into the relationship between breastfeeding patterns and height and weight development in babies.
Include additional variables: Considering additional variables such as socioeconomic factors, dietary habits, and individual health conditions can provide a more comprehensive understanding of the factors influencing height and weight development in infants.

Overall, these recommendations aim to promote informed decision-making regarding breastfeeding patterns and support healthy growth and development in infants. It's essential to consult with healthcare professionals and consider individual circumstances when making choices about breastfeeding and infant nutrition.

### Limitation with the Data
Based on the provided dataset and the insights derived from the analysis, the following limitations can be listed:

* Sample Size: The dataset includes information on 120 babies, with 30 babies selected for each breastfeeding pattern. While this sample size provides some insights, it may not fully represent the population of infants or account for potential variations within different demographics or regions. A larger sample size would enhance the reliability and generalizability of the findings.

* Representativeness: The dataset was collected from a single hospital in Port Harcourt, Rivers State, Nigeria in 2015. Therefore, the findings may not be applicable to infants from other regions or countries with different socio-cultural backgrounds, healthcare systems, or dietary practices. The data may be limited in its ability to capture the full diversity of breastfeeding patterns and their impact on growth.

* Other Factors: The analysis focuses primarily on the impact of breastfeeding patterns on height and weight, but it does not account for other potential influential factors. Variables such as genetics, overall nutrition, individual growth rates, socioeconomic status, and maternal health can also play a role in an infant's growth and development. The dataset's limited scope restricts the ability to explore these factors fully.

* Lack of Longitudinal Data: The dataset provides information on height and weight measurements at specific time points within the first six months of an infant's life. However, to fully understand the long-term impact of breastfeeding patterns on growth, longitudinal data tracking the infants' growth over an extended period would be valuable.

* Generalizability: The findings and insights derived from this dataset may not be directly applicable to all infants or populations. Cultural, socioeconomic, and regional variations in breastfeeding practices and growth patterns can influence the generalizability of the results. Therefore, caution should be exercised when extrapolating these findings to other contexts.

Overall, while the dataset provides valuable insights into the impact of breastfeeding patterns on height and weight, these limitations should be considered when interpreting the results and drawing conclusions. Further research with larger and more diverse samples, incorporating additional variables or factors, and employing rigorous statistical analysis would enhance the understanding of the relationship between breastfeeding patterns and infant growth. 

Thank you for taking your time to go through this project.🫂

Your comments and recommendations will be highly appreciated. 🤗

Kindly connect with me on [Twitter](https://twitter.com/Eddie_Gregs?t=dF3996shVxvPJTePTtxDdw&s=09) and [LinkedIn](https://www.linkedin.com/in/blessing-ekwere-857326216)









