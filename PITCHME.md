---

## Continuous Integration in Software Development
##### by Omar Elazhary

---

### Agenda
- Introduction to Continuous Integration (CI)
    - Continuous software engineering
    - How it all fits together
- Research Background
    - Information Gathering
    - Research Domains
    - Mapping the Landscape
- Areas of Interest
    - Build-time reduction
    - CI as a communication channel

---

### Introduction to CI

> "Continuous Integration is a software development practice where members of a team integrate their work frequently leading to multiple integrations per day.
> Each integration is verified by an automated build to detect integration errors as quickly as possible." - Martin Fowler

+++

### Continuous Software Engineering

+++?image=/visual-aids/continuous-swe.png&size=75% auto

@title[CI Tools]

+++?image=/visual-aids/ci_tools.png&size=75% auto

@title[CI in Action]

+++

### How It All Fits Together

+++?image=/visual-aids/github_workflow.png&size=75% auto

@title[GitHub Flow]

---

### Research Background

+++

### Information Gathering

- Systematic literature review by Shahin et al.
![Research Progression](/visual-aids/research_progression_shahin.png?size=50%)

+++

### Research Domains

- Build- and Test Time Reduction
- Visibility and Awareness of CI Results
- Semi-Automated Continuous Testing
- Violations, Flaws, and Faults in CI
- Security and Scalability Issues in Pipelines
- Reliability of the Deployment Process

+++

### Mapping the Landscape

<iframe width="800" height="550" frameborder="0" scrolling="no" src="//plot.ly/~omazhary/5.embed"></iframe>

+++

### Current _Hot_ Topics

- Build Mining, Monitoring, and Analysis
    - Inferring Patterns from Builds
    - Correlating Build Patterns with Other "_Attributes_"
- Build Output Analysis
    - Predicting Build Success/Failure
    - Prediction Test Success/Failure
- Effects of Applying CI on Development/Quality

---

### Areas of Interest

+++

### Build-Time Reduction

+++

@title[Automation Quote]

> "The first rule of any technology used in a business is that automation applied to an efficient operation will magnify the efficiency.
> The second is that automation applied to an inefficient operation will magnify the inefficiency." - _Bill Gates_

+++

### Problem

Builds -depending on the system- can take too much time.

+++

### Anatomy of a Build

- Majority: Decrease Test Time
- Build does not consist solely of Tests
![CI Workflow](/visual-aids/ci_workflow.png?size=60%)

+++

### Possible Solution: Machine Learning (ML)?

- Possible Flow:
    1. Identify overhead from non-essential CI processes
    2. Propose optimizations per-stage of CI build:
        1. Provisioning
        2. Dependency Management
        3. Building (_actual_)
        4. Testing
- Possible Outcome:
    A framework for the application of ML in CI build optimization?

+++

### CI as a Communication Channel

+++

### The Great Wall of Log

![Travis Output](/visual-aids/travis_output.png?size=50%)

+++

### Other Interesting Interfaces

@title[CircleCI]

![CircleCI Output](/visual-aids/circle_output.png?size=50%)

+++

### Other Interesting Interfaces

@title[ConcourseCI]

![ConcourseCI Output](/visual-aids/concourse_output.png?size=50%)

---

### In Conclusion
