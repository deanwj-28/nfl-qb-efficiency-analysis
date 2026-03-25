**NFL Quarterback Efficiency Analysis (2023 Season)**

This project analyzes quarterback performance using play-by-play data to evaluate efficiency, consistency, and situational performance.

**Objective**
The goal of this analysis is to assess quarterback decision-making and effectiveness using advanced metrics commonly used in football analytics.

**Metrics Used**

	• EPA per Play (Expected Points Added): Measures overall impact on scoring potential 
	• Success Rate: Evaluates consistency by measuring how often plays achieve necessary yardage 
	• Situational Performance: 
		○ Red Zone Efficiency 
		○ 3rd Down Performance

**Tools & Technologies**
	
	• R 
	• dplyr 
	• ggplot2 
	
**Key Visualizations**

EPA per Play by Quarterback
![EPA Chart](outputs/epa_bar_chart.png)
EPA vs Success Rate
![EPA vs Success](outputs/epa_vs_success.png)

**Key Insights**

	• Quarterbacks with high EPA per play tend to generate explosive plays that significantly increase scoring potential 
	• Success rate highlights consistency, showing which quarterbacks sustain drives effectively 
	• Situational splits (3rd down, red zone) reveal performance under pressure and in high-leverage scenarios 

**Project Structure**

	• scripts/ → R code for analysis 
	• outputs/ → visualizations 
	• data/ → dataset reference 

 **Future Improvements**

	• Incorporate player tracking data 
	• Expand analysis to include receivers and route concepts 
	• Build predictive models for QB performance 
