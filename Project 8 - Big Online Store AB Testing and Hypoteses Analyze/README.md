# Big Online Store A/B Testing and Hypoteses Analyze
## by _Mila Widya Lestari_

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

Stay connected by following my instagram: [@milaalestari_](https://www.instagram.com/milaalestari_/)

## Features
> Data used in the first part of the project:
> 
> [**/datasets/hypotheses_us.csv**](https://raw.githubusercontent.com/milawidyalestari/data-analyst-ml-project/project8-online-store-ab-test/hypotheses_us.csv)
> 
> - Hypotheses — brief description of the hypothesis
> - Reach — user reach, on a scale of one to ten
> - Impact — impact on users, on a scale of one to ten
> - Confidence — confidence in the hypothesis, on a scale of one to ten
> - Effort — resources needed to test the hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the testing.
> 
> Data used in the second part of the project:
> 
> [**/datasets/orders_us.csv**](https://raw.githubusercontent.com/milawidyalestari/data-analyst-ml-project/project8-online-store-ab-test/orders_us.csv)
> 
> - transactionId — order ID
> - visitorId — ID of the user who placed the order
> - date — date the order was placed
> - revenue — revenue from the order
> - group — A/B test group the user belongs to
> 
> [**/datasets/visits_us.csv**](https://raw.githubusercontent.com/milawidyalestari/data-analyst-ml-project/project8-online-store-ab-test/visits_us.csv)
> 
> - date — date
> - group — A/B test group
> - visitors — number of visitors on the specified date in the specified A/B test group
> - visits — number of visits on the specified date for the specified A/B test group

## Description
Business decision-making based on data is an essential practice in the online business world. It involves using data and analysis to make better decisions. This typically includes data collection, analysis, and interpretation to understand trends, patterns, and relationships that can provide valuable insights for the company.

Each metric has its specific function. However, we can't continuously monitor all metrics due to time or resource constraints. Therefore, it is essential to identify the metrics that will aid in the company's strategy and plans. The opportunities to influence business metrics are usually limited. Thus, several experiments are needed to determine which results have the most impact on the metrics.

To determine which experiment results will have the most significant impact on the metrics, integrated testing is necessary, such as polling, conducting surveys, or more advanced methods like A/B Testing. Imagine if a company changes the position of the cart in their online store app for all users. This could confuse users and cause the company to lose potential customers who were about to check out. To prevent this from happening, A/B testing is sometimes necessary, testing a smaller group rather than all customers, thus minimizing the loss of potential customers.

## Goal

To enhance our business decision-making process by leveraging data-driven insights, we aim to:

Identify Key Metrics: Determine and focus on the essential metrics that align with our company's strategic objectives and plans. Prioritize metrics that have the most significant impact on our business performance.

Conduct Effective Experiments: Implement integrated testing methodologies such as polling, surveys, and A/B testing to analyze the effects of changes on these key metrics. This approach helps us identify which changes yield the most substantial improvements.

Minimize Risks with Targeted Testing: Use A/B testing to test changes on a smaller, controlled group of users before rolling out to the entire user base. This will help us mitigate risks and avoid potential negative impacts on user experience and conversion rates.

Data-Driven Decision Making: Continuously collect, analyze, and interpret data to understand trends, patterns, and relationships. Use these insights to inform and guide strategic decisions, optimizing the user experience and maximizing business outcomes.

By systematically applying these practices, we aim to enhance our ability to make informed, data-driven decisions that drive growth and improve overall business performance.
