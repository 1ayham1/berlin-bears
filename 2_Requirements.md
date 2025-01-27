# Requirements Elicitation

## Solution Consideration Factors

- `Volatility`: **Level 2/5**. A given user story will be minimally changing. However new stories may be added.
- `Uncertainty`: **Level 4/5**. Various risk factors need to be considered. (more elaboration is in the `Solution Section`). We expect a considerable reduction after some iterations.
- `Complexity`: **Level 4/5**. The system is integrated with another solution. Changes in the original solution may be reflected on the proposed extension
- `Ambiguity`: **Level 1/5**. Requirements can be easily understood and improved based on closed feedback. 

# Functional Requirements 
## List of Actors

Generally speaking, the engagement model should provide support to the following categories:

> **`Clients`**: with a goal of building a community, education and increased awareness

> **`Clinics`**: with a goal of establishing a baseline tests for clients, gathering & analyzing results, reporting on changes and attract investors.

> **`Dieticians`**: with a selective access to medical information about the customer, the goal is supporting one-on-one advice for engaged customers.  

> **`Family Foods`**: with the objective of knowing which Transactional Customers are potential for the onboarding process. 

<br>
<ins> Examples are listed below </ins>

1. University Student
2. Working Mother
3. Fitness Instructor
4. Local Elementary Classroom Teacher
5. Social media influencer
6. Busy Worker
7. User with special dietary requirements
8. Healthcare Professional
9. Investor
10. Transactional Customer
11. Medical Provider
12. Dietitian
## User Stories

From an Agile Perspective the `A User Story` should be:
``` 
(1) Independent (2) Negotiable (3) Valuable

(4) Estimable (5) Small (6) Testable. 
```
<br>
1. As <ins>a busy university student</ins>, I want to order a healthy meal anytime, so that I focus on my study

> `Main Feature`: **availability**. 

- The system shall enable online ordering (mobile phone, web interface, calling.. )
- The system shall offer delivery/pick up options 

2. As <ins>a working mother</ins>, I want to return the order and receive a new one easily and immediately if it does not meet my expectations , so that I keep up with my busy schedule

> `Main Feature`: **customer feedback**.

- The system shall enable flexible return of order items
- The system shall enable and gather feedback
- The system shall predict customer behavior 

3. As <ins>a fitness instructor</ins>, I want to flexibly preorder a healthy meal, so that I keep my busy schedule

> `Main Feature`: **preorder**.

- The system shall enable saving orders
- The system shall enable a scheduled delivery

4. As <ins>a local elementary classroom teacher</ins>, I want to place massive orders where I can selectively choose the gradients, so that  I can teach my students about healthy food in my cooking class

> `Main Feature`: **massive selected order**

- The system shall support multiple orders
- The system shall enable gradient selection

5. As <ins>a social media influencer</ins>, I want to take photo of the healthy meal, so that I can post it on my social media channel

> `Main Feature`: **photo capture**

- The system shall enable taking/storing/uploading images

6. As <ins>a busy worker</ins>, I don’t have time to browse the app and I want to record the order of my favorite healthy food on my way to work, so that I can focus on other tasks. 

>`Main Feature`: **voice recognition and processing**

- The system shall enable recording an order
- The system shall enable automatic processing and delivery

7. As <ins>a person with special dietary requirements</ins>, I want to be able to easily access the ingredients of my meal, so that I am maintaining my demands

> `Main Feature`: **data visualization**

- The system shall provide nice visualization on available gradients

8. As <ins>a healthcare professional</ins>, I want to be able to share feedback easily and provide system rating, so that deliver high quality recommendations to my patients 

> `Main Feature`: **System evaluation**

- The system shall easy rating mechanism
- The system shall provide accessible forms for feedback

9. As <ins>an investor</ins>, I want to see various statistics and analytics of how various stakeholders benefit from the system, so that I make a supporting decisions

> `Main Feature`: **Data Analytics**

- The system shall enable gathering data with customer consent and legal regulations
- The system shall provide smart predictive analytics 
- The system shall provide useful reports on history data


10. As <ins>a transactional customer</ins>, I want to receive concise, coherent, personalized and motivating information, so that I become an engaged customer.

> `Main Feature`: **marketing and awareness**. 

- The system shall store customer order and wishes.
- The system shall analyze customers' wishes, based on past orders and generate suitable promotions that address their needs.


11. As <ins>a medical provider</ins>, I want to view reports on various customers, so that I provide them with a professional advice with regard to their health and nutrition.

> `Main Feature`: **validation and follow up**. 

- The system shall enable health professionals to view reports on customers and their nutrition habits, choices and meal ingredients
- The system shall provide a mechanism at which health professionals can generate and write feedback
- The system shall enable users to view professional reports

12. As <ins>a dietitian</ins>, I want to send personalized advice to customers given their health conditions and various requirements, so that I satisfy their expectations and meet their goals.

> `Main Feature`: **professional advice**. 

- The system shall enable dietitians to review current customer nutritional habits
- The system shall enable dietitians to provide feedback and suugestions.


# Requirements in the Broad Sense 

From a broader perspective and to drive better communication and understanding, requirements can be divided into 6 categories. A general overview is provided at this iteration and further analysis is addressed in subsequent increments. More details can be found in PMI Guide to Business Analysis

> **Business requirement**:
- High-level needs of the organization
- Measurable represeentations of goals 

> **Stakeholder requirement**:
- Needs and desires
- Managed through Stakeholder management/engagement plan as well as communication plan

> **Solution requirement**:
- Features, functions and characteristics of the product
- Should meet Stakeholder and Business requirements
- Divided into:
    1. `Functional requirement`: reflecting the behavior of the product (listed above) 
    2. `Nonfunctional requirement`: the environmental conditions or qualities required for the product to be effective. (visual, usibility,maintainability, performance ...)

> **Transition requirement**: 
* training requirements

> **Project requirement**: 
* focus on project execution

> **Quality requirement**: 
* conditions to validate the completion of deliverables/fulfillment of project requirements

<br>
<hr style="height:2px;border-width:0;color:gray;background-color:gray">

##  [<-- Back](1_BusinessAnalysis.md) | [Home](README.md) | [Next -->](3_Solution.md)




