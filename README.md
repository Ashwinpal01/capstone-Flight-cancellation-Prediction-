# Capstone Project -Flight-cancellation-Prediction-

Overview:
Traditional Flight Cancellation Flaws:  
Flight cancellations disrupt passenger plans, causing inconvenience and potential financial losses. It strain airport resources, impacting operational efficiency, and can harm an airline's reputation, leading to decreased customer trust. 
Let’s Leverage Machine Learning :
Develop a machine learning model that predicts early whether a flight will be cancelled based on historical data, enabling the airline to take pre- emptive measures to minimize cancellations and optimize its operations.

BUSINESS INFERENCE:
1.Positive Influencers on Cancellation Probability:
   - Flights arriving at a destination at a later time (WHEELS_ON: 0.116894) and those in more recent years (Flight Year: 0.041553) tend to 
     have higher odds of being cancelled.
   - Longer CRS_ELAPSED_TIME (0.007258) are also associated with increased cancellation odds.
2.Contributors with Minimal Impact:
   - Features such as DEST, ORIGIN, CANCELLATION_CODE, and AIRLINE_CODE_en have relatively small coefficients 
    (ranging from 0.000019 to 0.000421), indicating minimal impact on the likelihood of cancellation.
3.Negative Influencers on Cancellation Probability: 
Delay factors like DELAY_DUE_WEATHER and DELAY_DUE_SECURITY suggested moderate impact on cancellation odds.
           -   Longer DISTANCE (-0.000130) and flights scheduled in certain months (Flight Month: -0.014948) are 
             associated with  slightly lower cancellation odds.

BUSINESS SOLUTIONS:
1.Optimize Operational Efficiency:
Focus on reducing Taxi In and Taxi Out times to improve operational efficiency. Although shorter times are associated with a slightly higher likelihood of cancellation, overall operational efficiency can be enhanced by streamlining ground operations and reducing taxi times without compromising safety.

2.Manage Delays Proactively:
Implement measures to minimize airtime, reduce departure delays, and ensure timely wheels-off times to decrease the odds of cancellation and enhance overall flight punctuality.

3.Weather and Seasonal Considerations:
Taking into account seasonal variations and weather conditions when scheduling flights. Although delay factors like DELAY_DUE_WEATHER have moderate impact on cancellation odds, we can consider their potential influence on overall flight operations.

Dataset Link:https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023?select=flights_sample_3m.csv








