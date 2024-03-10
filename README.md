# Media Rail Repositioning Analysis for Cooking Equipment Company

## Overview
A cooking website sells cooking equipment. They want to improve their product page. The product page has a rail with media (images or videos). Up until now, they have had a horizontal rail, a UX designer suggested having a vertical one. As a data analyst in the company, you suggested doing an AB test. You now have the results of the test and need to advise the company on whether they should ship the feature (vertical media rail) or not.
This project investigates the effects of changing the media rail from horizontal to vertical on a cooking equipment company's website. Utilizing hypothesis testing, our goal is to understand the alteration's impact on user engagement and sales metrics.

## Objectives
● Formulate and define a hypothesis for a research question
- What is the business problem you are trying to solve?
- Why does it matter to the company?
- What are the benefits and drawbacks of the new variant in your opinion?
- What is the hypothesis you are trying to test? What is the null hypothesis, what is the alternative hypothesis?
● Apply the most appropriate statistical technique to evaluate a hypothesis, using a data analysis tool
- Why is an AB test a good method for testing the hypothesis?
- Propose another method that could have been used and compare pros and cons of an AB test vs this method.
- What metrics did you select in the AB test, and why? What is the primary metric? Are there other metrics you wished you had?
- How do the distribution of your metrics compare between the two variants? Show me plots comparing the distributions.
- What test did you apply? How did you specify your test and why (type of test, underlying distribution,parameters of the distribution, sample size, p-value...)
- What is the result of the test?
- What do you recommend the company to do?

## Data Description
Data for the analysis comprises web analytics for both control and treatment group, including:
- Variant: Control group A and Treatment group B.
- Number of page views: How many times the product pages was viewed. (Apply for all products.)
- GMV (in $): Gross Merchandise Value, likelihood to total sales.
- Number of add to cart: How many times products were added to the cart.
- Clicks on media: The number of clicks on media content.
- Time on Page (sec): The amount of time spent on the page, in seconds.
- user_id: A unique identifier for each user.
## Hypotheses
We predict that by switching the media rail layout to a vertical orientation on product pages will **increase user engagement** on pages, resulting in **more clicks on media**, **more page views**, a **longer average time spent on the pages**, and ultimately, a higher likelihood of **product sales**.

## Methodology
Employing **t-tests** for continuous data, **Chi-square tests** for categorical data, **z-test** for proportional data, we analyze the impact of the repositioned media rail through A/B testing.

## Tools & Technologies
- **Data Analysis:** Python (Pandas, SciPy, Statsmodels)
- **Visualization:** Matplotlib, Seaborn, Pygwalker

## Results
Findings indicate:
- Increased user engagement with the vertical media rail.
- More users add to cart and conversion rates post-repositioning.
- Decreased bounce rates, indicating improved user interest.
- Increased page views suggesting deeper engagement.

## Conclusions
The vertical media rail has positively affected user engagement and sales, validating its implementation across the site.

## Recommendations
- **Implementation:** Adopt the vertical layout across all web pages.
- **Continuous Testing:** Further optimize through ongoing A/B testing.
- **Gather User Feedback:** Use feedback for continuous improvement.
- **User Surveys/Interviews:** Qualitative research for deeper insights.

## Future Directions
- Investigate the effect of additional design changes.
- Perform user segment-specific analyses for tailored insights.
