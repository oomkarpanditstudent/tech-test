# Interview Exercise

## Details
This interview is designed to test your understanding of writing integration tests. There is boilerplate code to get started but you should apply your understanding of good framework structure, good test structures and good coding standards. Rememer this is an exercise designed for SDETs it is just as important to apply good testing practices as it is coding standards. 

An FAQ is provided at the bottom of this README for additional help.

<br>

# Getting Started
## 1. Install Dependencies
Install dependencies, run this from the root dir, it will install dependencies for both subprojects (backend and frontend)

```bash
npm run appstart
```

Frontend at [https://localhost:3001](http://localhost:3001)



# The exercise
**Write one or more tests that satisfies the following test scenario**
```gherkin
Given I navigate to the Brand Table
When I sort by revenue descending 
Then the brands are correctly ordered by revenue
```
<br>

# FAQ 
> What is a 'Brand Table'?

This is what we call a Brand Leader Board. It represents the best performing Brands within a Market. 

This is a representative insight that we have built for our customers. It simply shows the performance of each brand that sells products within a specific market. In this case, Flat Panel TVs in GreatBritain within a specific time period.

Whilst this data is not 'real' it is representative.

-----

> Can I use the internet?

yes, but copying and pastng from StackOverflow and crossing your fingers will lose points.

-----

> What if I get stuck?

This is a pairing exercise; ask for help, talk through your thinking. We are looking for team members not test monkeys.

----

> I have never used Cypress, can I use another UI test tool?

No, we have included the example helper tests that Cypress provides out of the box. They are in `cypress/integration/examples/`. Again, use your pairing partner. 
