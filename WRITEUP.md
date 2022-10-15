# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
    VM is more expensive and requires more setup, it's scalable but it's considerbaly harder to manually spin multiple vm and configure them to a load balancer. VM might be not as avaliable because more things could wrong. App Service workflow is much easier to get into.
- *Choose the appropriate solution (VM or App Service) for deploying the app*
        App Service
- *Justify your choice*
    For now, the blog does not have many visitors nor any demanding content to publish. App Service is much easier to work with, and far less expensive, it's also easier to scale if my blog went viral!

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I'll probably won't change my decision unless I'm working with something that won't work with App Service and requires manual deployment to a VM.
All and all I'm very happy with it.