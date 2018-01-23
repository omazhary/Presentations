---

## Contribution Process Information Flows and Project Health Perception
##### by Omar Elazhary

---

### Agenda
- Motivation
- Research Questions
- Information Flows
- Continuous Software Engineering
- Interpreting Project Health
- Next Steps

---

### Motivation

+++

@title[Motivation description]

- How do I get other developer to "invest" themselves in my project?
- Which project to include in my platform?
- Tales from the Front
    * All for Accounting
    * SAP

+++?image=/visual-aids/mercaware.png&size=75% auto

@title[All for Accounting Main]

+++

@title[All for Accounting Convo]

- _"Let's go open-source!!"_
- "Why?"
- _"More developers for little to no cost!"_
- "How??"

+++?image=/visual-aids/sap.png&size=65% auto

@title[SAP Main]

+++

@title[SAP Convo]

> "Oh come on Omar, you don't really want to re-invent the wheel, do you?" - Stefan Weber

---

### Research Questions

+++

@title[Questions]

1. How is information propagated within the contribution process?
2. How does information propagation affect people's perception of project health?

---

### Information Flows

+++?image=/visual-aids/sampling.png&size=75% auto

+++?image=/visual-aids/DFD_lvl01.png&size=65% auto

---

### Continuous Software Engineering

> "Continuous software engineering refers to the organizational capability to develop, release, and learn from software in rapid parallel cycles."

J. Bosch, “Continuous software engineering: An introduction,” in Continuous Software Engineering. Springer, 2014, pp. 3–13.

+++?image=/visual-aids/cse_workflow_old.png&size=65% auto

+++

### Continuous Integration (CI)

1. Retrieve source code
2. Compile source code
3. Execute:
    - Unit Tests
    - Integration Tests
    - Regression Tests
    - Static Analysis
4. Provide feedback

+++

### Continuous Delivery (CDE)

- Extends CI
- Adds the concept of a _Staging Environment_
- A successful build from a CI system will result in a production-ready release (if required by developer)

+++

### Continuous Deployment (CD)

- Extends CDE
- Adds the ability to deploy to a customer environment (i.e., _production_)
- A.K.A. _The Pipeline_

+++?image=/visual-aids/cse_workflow.png&size=65% auto

+++?image=/visual-aids/DFD_lvl02.png&size=65% auto

---

### Interpreting Project Health

+++?image=/visual-aids/ITIL_RequestFulfillment.png&size=25% auto

+++

### ITIL Request Fulfillment

- Customer Requests:
    - Additional Functionality
    - Modification of Existing Functionality
- Critical Success Factors (CSFs)
- Key Performance Indicators (KPIs)

+++

### CSFs and KPIs

- **CSF:** Efficient and Timely
    - **KPI:** Mean Service Request Handling Time
    - **KPI:** Number and Percentage of Requests Completed in Target Time
- **CSF:** Only Authorized Requests
    - **KPI:** Percentage of Appropriately Authorized Completed Requests
- **CSF:** User Satisfaction
    - **KPI:** Measure of Satisfaction per Request

---

### Next Steps

- Inter-rater Agreement?
- Code Analysis
- Validate DFD Model
- Apply KPIs and Observe Outcome
    - Might need some sort of baseline
