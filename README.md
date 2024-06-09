# The Eduction Hub
EducationHub is a education network for everyone. 
> [!TIP]
> User is who using our platform on any devices both registered or non-registered. User can explore useful documents for education, scholarship, school information and more.

```mermaid
gantt
dateFormat  YYYY-MM-DD
title Education Hub
excludes weekdays 2024-06-01

section UX & Prototype section
Completed task            :done,    plan, 2024-05-01,2024-05-31
Prototyping               :active,  prototype, 2024-06-01, 15d
Education maps task               :         education, after prototype, 5d
School info              :         school_info, after education, 5d
````

## Features
- [ ] <strong> Education Roadmaps<strong>:
- [ ] Resume builder 
- [ ] Scholarship
- [ ] School Information
- [ ] Scholar Foundation

```mermaid
graph TD;
    Education-Hub-->User;
    Education-Hub-->Education-Roadmaps;
    Education-Hub-->Scholarship-Info;
    Education-Hub-->School-Info;
    Education-Hub-->Foundations;
```
