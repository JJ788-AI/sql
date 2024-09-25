# Assignment 1: Design a Logical Model

## Question 1
Create a logical model for a small bookstore. 📚

At the minimum it should have employee, order, sales, customer, and book entities (tables). Determine sensible column and table design based on what you know about these concepts. Keep it simple, but work out sensible relationships to keep tables reasonably sized. Include a date table. There are several tools online you can use, I'd recommend [_Draw.io_](https://www.drawio.com/) or [_LucidChart_](https://www.lucidchart.com/pages/).

![image](https://github.com/user-attachments/assets/ee2a34f6-3c26-4ddd-9904-cde345089506)

## Question 2
We want to create employee shifts, splitting up the day into morning and evening. Add this to the ERD.

![image](https://github.com/user-attachments/assets/2a29e9f6-4078-49c5-844a-3f0bb3498f0d)

## Question 3
The store wants to keep customer addresses. Propose two architectures for the CUSTOMER_ADDRESS table, one that will retain changes, and another that will overwrite. Which is type 1, which is type 2?

_Hint, search type 1 vs type 2 slowly changing dimensions._

Bonus: Are there privacy implications to this, why or why not?
```
```
![image](https://github.com/user-attachments/assets/27566fb1-aabf-4428-acaa-6530cb4e6f3c)

Answer :When retaining historical customer addresses, significant privacy risks arise. First, storing sensitive information like past addresses increases the risk of data breaches, potentially leading to identity theft—additionally, compliance with privacy regulations. To comply, organizations must ensure they obtain explicit customer consent when collecting and retaining historical addresses. Customers should also know how their data will be used and protected to maintain trust. Lastly, implementing the right to be forgotten can add complexity, as organizations must effectively manage deletion requests. Therefore, balancing retaining historical data and protecting sensitive information is crucial.
```
```
## Question 4
Review the AdventureWorks Schema [here](https://imgur.com/a/u0m8fX6)

Highlight at least two differences between it and your ERD. Would you change anything in yours?
```
```

Answer:
1.The AdventureWorks schema is much more detailed attributes such as vendor, employee pay history 
2.The colour coding structures. Such as Human resources, Sales, Person, Production, and Purchasing. 
The AdventureWorks schema is more detailed and complex, encompassing a broader range of hierarchical relationships. However, it's essential to consider the actual use and specificity of the data when designing a database. In contrast, the bookstore ERD excels in targeted functionality and data capacity. Nevertheless, the ERD can be continuously improved by adding more detailed elements to adapt to evolving business needs. This way, the bookstore system can maintain its efficiency while offering richer features and a better customer experience.
```

# Criteria

[Assignment Rubric](./assignment_rubric.md)

# Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `September 28, 2024`
* The branch name for your repo should be: `model-design`
* What to submit for this assignment:
    * This markdown (design_a_logical_model.md) should be populated.
    * Two Entity-Relationship Diagrams (preferably in a pdf, jpeg, png format).
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sql/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `model-design`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-4-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
