A/B Testing Project - from an international online store

Task

You've received an analytical task from an international online store. Your predecessor failed to complete it: they launched an A/B test and then quit (to start a watermelon farm in Brazil). They left only the technical specifications and the test results.

Technical description

* Test name: recommender_system_test
* Groups: А (control), B (new payment funnel)
* Launch date: 2020-12-07
* The date when they stopped taking up new users: 2020-12-21
* End date: 2021-01-01
* Audience: 15% of the new users from the EU region
* Purpose of the test: testing changes related to the introduction of an improved recommendation system
* Expected result: within 14 days of signing up, users will show better conversion into product page views (the product_page event), product card views (product_card) and purchases (purchase). At each of the stage of the funnel product_page → product_card → purchase, there will be at least a 10% increase.
* Expected number of test participants: 6000


Instructions on completing the task

* Describe the goals of the research
* Explore the data
   * Does it need converting types?
   * Are there any missing or duplicate values? If so, what's their nature?
* Carry out exploratory data analysis
   * Study conversion at different funnel stages
   * Is the number of events per user distributed equally in the samples?
   * Are there users who enter both samples?
   * How is the number of events distributed by days?
   * Think of the possible details in the data that you have to take into account before starting the A/B test?
* Evaluate the A/B test results
   * What can you tell about the A/B test results?
   * Use the z-criterion to check the statistical difference between the proportions
* Describe the conclusions on the EDA stage, as well as on the evaluation of the A/B test results
