# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
APP SERVICE:  App Service solutions operate on a pay-as-you-go model, where you only pay for the resources consumed by your application, making it a more cost-effective option for CMS app. Furthermore, App Service provides high availability and automatic scaling without complex configuration, which is more suitable for lightweight app

VM: VMs involve managing and paying for the infrastructure, including the OS and software licenses. In addition, VM offers high availability options and more flexibility like vertical and horizontal scaling, which requires additional configuration and management effort. For bigger scale project and application, this approach is more cost-efficient and easier to maintain and scale.

My Choice: I chose App Service because the CMS app is more efficient in cost and easier to deploy. The requirements for compute power is not too much, and the app configuration is straight forward and no need for high complex configuration. App Service should handle the deployment smoothly and also provide easy management of the CMS app. Also, App Service works great with Python too.

### Assess app changes that would change your decision.

For more complex requirements in function beside CRUD that relied on heavy-duty workload on the hardware, VM would be my choice. Another point to add is that on a larger scale, VM would be more reasonable in cost. 