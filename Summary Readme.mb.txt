# Kickstarting with Excel

## Overview of Project
	Louise is wanting to determine her best options for funding her next play.  The analysis will be over a nine-year period between 2009 and 2018.  
	Using this historical data, we will be able to determine when the best time is to start a project campaign as well as the best value to set for success.
### Purpose
	Louise is wanting to fund her next play project and wants us to analyze the best successful options for her.  
	Louise would ideally like to have the entire project funded though Kickstart funding to reduce her personal liability if the project is not a success.
## Analysis and Challenges
	Completing the analysis using outcomes backed on Goals as well as Theater outcomes vs launch.  The Outcomes based on Goal was completed using a Countifs formula
	 =COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"failed",Kickstarter!$R:$R,"plays").  While the Theater outcomes vs launch was completed using a Pivot table 
	='Theater Outcomes vs Launch'!.  The results of the analysis was conveyed using line charts, C:\Users\mike_\Desktop\Bootcamp\Module 1\Resources
### Analysis of Outcomes Based on Launch Date
       May and June are the best times of the year to launch a campaign.
### Analysis of Outcomes Based on Goals
	To ensure a successful campaign, the target amount should be between $1,000 and $5,000.  There is a slight decline in success for values between $5,000 and $10,000
### Challenges and Difficulties Encountered
	Some of the challenges with the analysis was ensuring the proper coding was used.  There were some difficulties in regard to formatting the formula correctly to 
	pull the proper information for analysis
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1) Second and Third quarter are a better time to start a campaign to fund plays
	2) Fourth quarter of the year has the lowest success rate for raising funds.
- What can you conclude about the Outcomes based on Goals?
	The most successful funding campaigns have maintained a value less than $10,000, with a significant drop in success with a campaign over $15,000
- What are some limitations of this dataset?
	One of the limitations of this dataset is that we are only comparing historical data from one source.  
	There are several different funding sources on the market and having the ability to use datasets from multiple funding vendors, we would be able to analyze which 
	service gets more traffic and compare successful against failed campaigns to help determine the best way to fund Louise's project.
	Another limitation to the data set is that it could have included zip codes.  Having the additional information could help identify geographic locations for success of
	funding.	
- What are some other possible tables and/or graphs that we could create?
	Some of the other charts/graphs that could be used to tell the analytic story to the client are Bar, Area and Combo.  The line graph was used in the current analysis, 
	but the other charts mentioned could easily be substituted.
