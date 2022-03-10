# AWS-Lex
Unit 13 Homework Assignment - The Power of the Cloud and Unsupervised Learning
----

It is time to take what I have learned about unsupervised learning and the AWS services and apply it to new situations. For this assignment,I needed to complete one of two (not both) challenges. 

I went with

# Option 1: Robo Advisor for Retirement Plans

I was hired as a digital transformation consultant by one of the most prominent retirement plan providers in the country; they want to increase their client portfolio, especially by engaging young people. Since machine learning and NLP are disrupting finance to improve customer experience, I decided to create a robo advisor that could be used by customers or potential new customers to get investment portfolio recommendations for retirement.

I used Amazon Lex to create a RoboAdvisor that takes the user's name and age and helps plan for retirement. I then utilizled a lambda function to make the bot more dynamic. Here is a demonstration.

![Robo Advisor test](amazonlex.gif)

## For User Input Validation:

The age should be greater than zero and less than 65 and the investment_amount should be equal to or greater than 5000.

## Depending on how risky you want your investment to be, the recommendations are as follows: 

none: "100% bonds (AGG), 0% equities (SPY)"

very low: "80% bonds (AGG), 20% equities (SPY)"

low: "60% bonds (AGG), 40% equities (SPY)"

medium: "40% bonds (AGG), 60% equities (SPY)"

high: "20% bonds (AGG), 80% equities (SPY)"

very high: "0% bonds (AGG), 100% equities (SPY)"

## *Video labeled amazonlex.mov demostrates the RoboAdvisor I created.*
