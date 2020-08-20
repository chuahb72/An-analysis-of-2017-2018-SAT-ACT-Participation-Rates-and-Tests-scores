# Problem Statement

Since the release of the new SAT format in March 2016, the national participation numbers has steadily increased from 1.63M test takers in 2016 (old format) to 1.72M in 2017 to 2.14M in 2018. However SAT adoption continue to fall below ACT participation rates.

This study was designed to analyze 2017 and 2018 SAT & ACT tests participation rates and test scores among the 51 different states in America. Trends and correlations will be analyzed and presented.

It also seek to identify any states with very significant increase in participation rate and conclude the reason(s) for their increase.

Recommendations will be proposed to apply study findings to further improve participations rates in selected state(s) should the opportunity presents itself.



# Executive Summary
- The average state SAT participation rate has improved from 39.8% in 2017 to 46.6% in 2018/
- In the same period, the average state ACT participation rate has decreased from 65.3% in 2017 to 61.6% in 2018/
- SAT vs ACT participation rates in states tend to display an almost "binary" relationship. Majority fo the students within the state tend to either take SAT or ACT.
- Typical participation rate distributions are bimodal or multi modal skewed to extreme data range
- For both SAT and ACT, participation rates are NEGATIVELY correlated to Test scores.
- Likewise, the SAT tests/sub-tests scores are also NEGATIVELY correlated to the ACT tests/sub-test.
- However this correlation should not be mistaken as causation!
- It is well understood that student from low participation rate states are usually the most prepared, ambitious high schoolers taking both the SAT and ACT. These students tend to score higher, effectively raising the state's average.
- Therefore the state's average SAT tests score will only be meaningful and representative for states with participation rates more than 20% (https://blog.prepscholar.com/average-sat-scores-by-state-most-recent)
- By excluding the participation rates and just comparing the test scores distributions, it is clear that both sets of tests and sub-tests show very similar distributions histograms indicating that SAT will be a viable substituition for college entry evaluation.
- Typical test scores distribution are bimodal or multi modal with central tendency.
- There are no significant changes in SAT/ACT Test/sub-test scores from 2017 to 2018
- Between 2017 and 2018, the states of Colorado, Illinois and Rhode Island saw the biggest jump in SAT participation. The main reasons for the increase are usually state legislation relating to manadatory SAT test.
- https://coloradosucceeds.org/policy/2018-colorado-student-test-scores-6-things-you-need-to-know/
- Funding from state and Non profit organization providing free SAT test were very well received further boosting participation rates.
https://www.coloradokids.org/more-colorado-high-school-students-participate-in-state-assessments-after-shift-to-psat/
- Research also shows that Democrat leaning states are showing higher SAT adoptions.
- We recommend that College board to focus on working with various States department of Education. Special focus and effort to reach out to state whereby there are no legislation that mandates taking of either the SAT or ACT. Convert them not just for SAT but beginning from Pre-SAT.
- College Board should also continue effort with States governments, Schools and Non Profit Organizations on fundings for Free SAT test, College Application fee waivers etc.
- States best targetted for imporvement should be Democrat leaning or neutral, no existing legislation to mandate ACT test and those that have expiring contracts with ACT board.



# Methodology
###### Exploratory Data Analysis
- Data import from internal source and external sources
- Data comparison between internal and external source to identify discrepancies
- Data cleaning, error correction, dtypes correction, dropped unwanted, null data
- Data columns renaming
- Datasets merging

###### Data Visualization
- General summary statistics
- Correlation matrices, heatmaps, paired plots to quickly surface correlated parameters
- In depth analysis for correlated parameter

##### External Research
- Identify states that showed significant SAT participation rates increease in 2018
- Web research to determine reasons for various trends
- Identify at least one other state to potentially apply the findings from above

##### Conclusion and Recommendations
- Present key findindgs
- Call to Action message



# Data

- 2017 SAT data (../data/sat_2017.csv)
- 2017 SAT data external source (../data/sat_2017_ext_source.csv)
    - data source: blog.collegevine.com
    - https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/
- 2017 ACT data (../data/act_2017.csv")
- 2017 ACT data external source (../data/act_2017_ext_source.csv)
    - data source: www.act.org
    - https://www.act.org/content/dam/act/unsecured/documents/cccr2017/ACT_2017-Average_Scores_by_State.pdf
- 2018 SAT data (../data/sat_2018.csv)
- 2018 SAT data external source (../data/sat_2018_ext_source.csv)
    - data source: ipsr.ku.edu
    - https://ipsr.ku.edu/ksdata/ksah/education/6ed16.pdf
- 2018 ACT data (../data/act_2018_updated.csv)
- 2018 ACT data external source (../data/act_2018_ext_source.csv)
    - data source: psr.ku.edu
    - https:http://ipsr.ku.edu/ksdata/ksah/education/6ed16a.pdf

### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|states|object|sat_2017, act_2017, sat_2018, act_2018|individual states of America|
|sat_2017_part_rate|int|sat_2017|state's sat participation rate expressed in a percentage for the year)|
|act_2017_part_rate|int|act_2017|state's act participation rate  expressed in a percentage for the year)|
|sat_2018_part_rate|int|sat_2018|state's sat participation rate expressed in a percentage for the year)|
|act_2018_part_rate|int|act_2018|state's act participation rate expressed in a percentage for the year)|
|sat_2017_erw|int|sat_2017|state's sat average Evidence-Based Reading and Writing score for the year)|
|sat_2018_erw|int|sat_2018|state's sat average Evidence-Based Reading and Writing score for the year)|
|sat_2017_math|int|sat_2017|state's sat average Math score for the year)|
|sat_2018_math|int|sat_2018|state's sat average Math score for the year)|
|sat_2017_total|int|sat_2017|state's sat average Total score for the year)|
|sat_2018_total|int|sat_2018|state's sat average Total score for the year)|
|act_2017_english|float|act_2017|state's act average English score for the year)|
|act_2018_english|float|act_2018|state's act average English score for the year)|
|act_2017_math|float|act_2017|state's act average Math score for the year)|
|act_2018_math|float|act_2018|state's act average Math score for the year)|
|act_2017_reading|float|act_2017|state's act average Reading score for the year)|
|act_2018_reading|float|act_2018|state's act average Reading score for the year)|
|act_2017_science|float|act_2017|state's act average Science score for the year)|
|act_2018_science|float|act_2018|state's act average Science score for the year)|
|act_2017_composite|float|act_2017|state's act average Composite score for the year)|
|act_2018_composite|float|act_2018|state's act average Composite score for the year)|



# Conclusion
- Despite Test scores being negative correlated to participation rates, SAT and ACT scores distribution are similar.
- SAT can be a viable replacement for ACT in any states. Colorado has surpassed National Averages even during it's first year of full implementation.
- States that show remarkable SAT adoption rate increase in 2018 have the following success factors
    - State department of education making SAT test mandatory even from Pre-SAT levels
    - Fundings from state coffers, schools and non-profit organizations to make SAT test free
    - Democrat leaning states also show better inclination for SAT adoption


# Recommendation
- Identify states that offers more opportunity for higher SAT adoption
    - Non-existing or expire ACT mandatory test
    - Democrat leaning or neutral
- Engage state's department of education and work towards mandatory SAT and Pre-SAT adoption.
- Actively promote factors that favors SAT adoption
    - Smart reductions in testing and a switch to more relevant assessments in high school.
    - Switching from the PARCC test to the Pre-SAT, ninth grade participation
- Work with state, schools, non-profit organization to gather funding for free SAT test, college application fees waiver or other financial assistance.






