# Project Description
You are an analyst at a big online store. Together with the marketing department, you've compiled a list of hypotheses that may help boost revenue.
You need to prioritize these hypotheses, launch an A/B test, and analyze the results.

**Data Source:** [Practicum by Yandex.](https://www.practicum100.com/)  
I do not have the permission to share this dataset.

## Data Description
**Data used in the first part of the project**  
**Hypotheses dataset**
* `Hypothesis` — brief descriptions of the hypotheses
* `Reach` — user reach, on a scale of one to ten
* `Impact` — impact on users, on a scale of one to ten
* `Confidence` — confidence in the hypothesis, on a scale of one to ten
* `Effort` — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

**Data used in the second part of the project**  
**Orders dataset**
* `transactionId` — order identifier
* `visitorId` — identifier of the user who placed the order
* `date` — of the order
* `revenue` — from the order
* `group` — the A/B test group that the user belongs to

**Visits dataset**
* `transactionId` — order identifier
* `visitorId` — identifier of the user who placed the order
* `date` — of the order
* `revenue` — from the order
* `group` — the A/B test group that the user belongs to

## Libraries Used
Pandas, Datetime, Numpy, Math, Scipy.stats, Matplotlib.pyplot, Seaborn, Plotly.express
