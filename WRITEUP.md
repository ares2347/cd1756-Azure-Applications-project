# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
APP SERVICE: Deploy through App Service is fairly easy with a reasonable cost. The CI/CD with Githubs Action is fast, convenient and easyto setup. A minor draw-back is that the cost is charged constantly even though no one is using it.

VM: Wider range of choice for customization. Easy to scale, good availability. For a light weight app, VM is a bit excessive

My Choice: I chose App Service because the CMS app is lightweight and no need for complex configuration. App Service would be a better choice since it is pretty straightforward and easier to monitor

### Assess app changes that would change your decision.

For more complex requirements in function beside CRUD that relied on heavy-duty workload on the hardware, VM would be my choice. Another point to add is that on a larger scale, VM would be more reasonable in cost. 