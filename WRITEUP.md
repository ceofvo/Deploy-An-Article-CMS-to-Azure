# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*

Costs - VMs has lower up-front cost compared to purchasing and maintaining hardware while for App Service the cost varies based on the plan you choose. There are three different tiers - Dev/Test, Production, and Isolated.

Scalability - Both VMs and App Service provides high scalability however for App Service there are hardware limitations, such as a maximum of 14GB of memory and 4 vCPU cores per instance.

Availability - Both VMs and App Service provide high availability.

Workflow - VMs support of both Linux and Windows VMs. There are multiple types to choose from, such as compute or memory-optimized VMs, along with varying amounts of CPU, RAM and storage. However for App Service offers continuous deployment model using GitHub, Azure DevOps, or any Git repo, auto-scaling and support of both Linux and Windows environments.

- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

For the app the appropriate solution will be an App Service because it enables me as a developer to developer to focus on the application while Azure takes care of the infrastructure. In addition it enables me to deploy code updates continously using GitHub without having to worry about OS or hardware.


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the app requirements grow such that maximum of 14GB of memory and 4 vCPU cores per instance available for App Service is not longer sufficient I will have to use a VM which provides varying amounts of CPU, RAM and storage as I may need. In addition if I need to install custom OS or software on the server to accomodate some new features for a language not currently supported by the Azure App Service, I will have to switch to VMs.