# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

_For **both** a VM or App Service solution for the CMS app:_

- _Analyze costs, scalability, availability, and workflow_
- _Choose the appropriate solution (VM or App Service) for deploying the app_
- _Justify your choice_

### Decisions and Comparisons

#### Why I choose App Service

I have choosen app service to deploy this service over virtual machines because first, the application is lightweight and app service is good at that. Second because my budget is tight and app service is less costly compared to virtual machines

### Comparison between Virtual Machines and App Service

#### Price

`Virtual Machine` is more expensive than `App Service` because it is still running, consuming resources, like CPU and memory, even though when the application is not in use.

Often to use the `App service` is necessary to pay for a plan. Using the `Virtual Machine` you should pay for usage (pay-as-you-go).

#### Scalability

`Azure App Service` has constraints in terms of scalability.
`Azure VMs` are preferred for apps, which have the scope to expand for the future.

#### Maintenance

`Virtual Machine` requires much more time and maintenance than App Services. Using `App service`, developers only need to focus int the technologies used on the application.
`Virtual Machine` is much better for applications that need more maintainability and changes.

#### Effort to developing an application

Using `App Service` is much simpler and faster than developing using `Virtual Machines`

### Assess app changes that would change your decision.

_Detail how the app and any other needs would have to change for you to change your decision in the last section._

I would choose virtual machines to deploy this application in future if I would require full
access and control of the resources like the operating system, network and security configurations, deployment, management among others. This is because app service offer a limited access to the host server.
