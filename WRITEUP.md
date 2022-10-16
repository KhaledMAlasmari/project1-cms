# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
    | 1 core 1.75 gb ram compute unit | Virtual machine                                     | App Service                                                     |
    |---------------------------------|-----------------------------------------------------|-----------------------------------------------------------------|
    | Costs                           | $65                                                 | $54                                                             |
    | Scalability                     | Scale sets is a bit harder to use                   | Auto scaling is built in which makes it easier to work with     |
    | Availability                    | 95% ~ 99.95% uptime depending on your configuration | 99.95% uptime for paid Apps, no guarantee for free/shared ones  |
    | Workflow                        | A bit tedious to use and deploy apps to it          | Using containerized apps makes deployment and config far easier |
- *Choose the appropriate solution (VM or App Service) for deploying the app*
        App Service
- *Justify your choice*
    For now, the blog does not have many visitors nor any demanding content to publish. App Service is much easier to work with, and far less expensive, it's also easier to scale if my blog went viral!

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I'll probably won't change my decision unless I'm working with something that won't work with App Service and requires manual deployment to a VM.
All and all I'm very happy with it.

