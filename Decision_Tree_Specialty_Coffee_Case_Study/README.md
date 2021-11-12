# Decision Tree Speciality Coffee

![Project Image](project-image-url)

 > The objective of this project is to help RR diner coffee make decision whether it should strike a deal with Hidden Farm coffee (China based Coffee farm) and continue buying coffee from Hidden Farm or strike the deal out and stop buying coffee from Hidden Farm. 
---
### Table of Contents

- [Description](#description)
- [Dataset](#Dataset)
- [Project goal](#goal)
- [License](#license)
- [Author Info](#author-info)

---

## Description

**RR Diner Coffee** sells two types of things:

- specialty coffee beans, in bulk (by the kilogram only)
- coffee equipment and merchandise (grinders, brewing equipment, mugs, books, t-shirts).

**RR Diner Coffee (three stores total)**, 
- 2 in Europe
- 1 in USA (flagshap store)
Everything is quality assesse in USA store, before being shipped out. Customers further away from the USA flagship store have higher shipping charges.

`RR Diner Coffee` **-->** `buys coffee from farmers` **-->** `processes it on site` **-->** `brings it back to the USA`**-->** `roasts it, packages it, markets it, and ships it (only in bulk, and after quality assurance) to customers internationally`. These customers all own `coffee shops` in major cities like New York, Paris, London, Hong Kong, Tokyo, and Berlin.

### **Current issue** ###

Now, RR Diner Coffee has a decision about whether to strike a deal with a legendary coffee farm (known as the Hidden Farm) in rural China: there are rumours their coffee tastes of lychee and dark chocolate, while also being as sweet as apple juice.

So our job here is To build a decision tree to predict how many units of the Hidden Farm Chinese coffee will be purchased by RR Diner Coffee's most loyal customers.

## Dataset
The dataset consists of a survey of 710 of the most loyal RR Diner Coffee customers, collecting data on the customers':

- age
- gender
- salary
- whether they have bought at least one RR Diner Coffee product online
their distance from the flagship store in the USA (standardized to a number between 0 and 11)
- how much they spent on RR Diner Coffee products on the week of the survey
- how much they spent on RR Diner Coffee products in the month preeding the survey
- the number of RR Diner coffee bean shipments each customer has ordered over the preceding year.

Survey contains also whether each customer participating in the survey whether would buy the Hidden Farm coffee, and some (but not all) of the customers gave responses to that question.

Decision condition: if more than 70% of the interviewed customers are likely to buy the Hidden Farm coffee, RR diner strikes the deal with the local Hidden Farm farmers and sells the coffee. Otherwise, you won't strike the deal and the Hidden Farm coffee will remain in legends only. There's some doubt about whether 70% is a reasonable threshold, but it'll do for the moment.

To solve the problem, we build a decision tree to implement a classification solution.

## Goal
This notebook uses decision trees to determine whether the factors of salary, gender, age, how much money the customer spent last week and during the preceding month on RR Diner Coffee products, how many kilogram coffee bags the customer bought over the last year, whether they have bought at least one RR Diner Coffee product online, and their distance from the flagship store in the USA, could predict whether customers would purchase the Hidden Farm coffee if a deal with its farmers were struck.

### Sourcing and loading
- Import packages
- Load data
- Explore the data

[Back To The Top](#decision-tree-speciality-coffee)

---

[Back To The Top](#decision-tree-speciality-coffee)

---

## License

MIT License

Copyright (c) [2021] [Isaac Ghebregziabher]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#decision-tree-speciality-coffee)

---

## Author Info

- LinkedIn - [ighebregziabher](https://www.linkedin.com/in/ighebregziabher)
- Github - [iabrahamus](https://www.github.com/iabrahamus)

[Back To The Top](#decision-tree-speciality-coffee)