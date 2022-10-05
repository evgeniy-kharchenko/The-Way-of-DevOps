# DevOps Culture
Компетенции для развития в ветке `DevOps Culture`:
```mermaid
graph LR
    DevOpsCulture{DevOps Culture}
    DevOpsCulture --> OCDV[Organisational capability development]
    DevOpsCulture --> ORDI[Organisation design and implementation]
    DevOpsCulture --> RLMT[Relationship management]
    DevOpsCulture --> MEAS[Measurement]
    DevOpsCulture --> ITMG[IT management]
    DevOpsCulture --> DLMG[Systems development management]
    DevOpsCulture --> ETDL[Learning delivery]

    OCDV --> RnD[Research and Development]
    OCDV --> PoC[Prove of Concepts]
    OCDV --> OrgCapAssessment[Organisation capability assessment]

    ORDI --> TeamAssessment[Team assessment]
    ORDI --> StrategyPlanning[Strategy Planning]

    RLMT --> PeopleManagement[People Management]
    RLMT --> ProblemManagement[Problem Management]
    RLMT --> ContinuousFeedback[Continuous Feedback]
    RLMT --> WorkwithStakeholders[Work with Stakeholders]
    RLMT --> Communications
    RLMT --> StrategyPlanning

    MEAS --> DORA[DORA Metrics]
    MEAS ---> RnDDevPractaises[Research Developer Practaises and Standards]
    MEAS ---> GoalSetting[Goal Setting]
    MEAS ---> KnowledgeManagement[Knowledge Management]

    ITMG ---> InfrastructureDesign[Infrastructure Design]
    ITMG ---> Budgeting[Budgeting]
    ITMG ---> Operations[Operations]
    Operations ---> Installation
    Operations ---> Updating
    Operations ---> Monitoring
    ITMG ---> StandardManagement[Management of it standards]
    ITMG ---> ServiceManagement[Service Management]
    ServiceManagement ---> SLA
    ServiceManagement ---> SLI
    ServiceManagement ---> SLO
    ITMG ---> Planning
    ITMG ---> Communications
    ITMG ---> StrategyPlanning
    ITMG ---> CHMG[Change Management]
    ITMG ---> Policy[Policy Management]

    DLMG ---> StrategyPlanning
    DLMG ---> SDLC

    ETDL ---> PeopleEducation[People Education]
```