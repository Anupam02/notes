Just as IaaS hides physical servers from VM consumers, platform as a service(PaaS) hiders operating systems from applications.
Developers write application code and define the application dependencies, and it is the platform's responsibility to create the necessary infrastructure to run, manage , and expose it.

12-Factor Applications
Th 12 factors are about making developers efficient by seperating code logic from data;
automating as much as possible; 
having distinct build;
ship;
and run stages;
and declaring all the applications dependencies;

If you consume all your infrastructure through a PaaS provider, congratulations, you already have many of the benefits of cloud native infrastructure. This includes platform such as Google App Engine, AWS Lambda, and Azure Cloud Services. Any successful cloud native infrastructure will expose a self-service platform to application engineers to deploy and manage their code.

Imp - Cloud native is not about running applications in containers. when
Netflix pioneered cloud native infrastructure , almost all its applications were deployed with virtual machine images, not containers. The way you package your applications doesn't mean you will have the scalability and benefits of
automations systems. Even if your applications are automatically built and deployed with a continous integration and continous delivery pipeline, it doesn't not mean you are benefiting from infrastructure that can complement API-driven deployments.
S
?? What is continous integration and continous delivery pipeline.

It also doesn't mean you only run a container orchestrator ( e.g., Kubernetes
and Mesos). Container orchestrators provide many platforms features needed in
cloud native infrastructure, but not using the features as intended means  your applications are dynamically scheduled to run on a set of servers . this is  a very good first step , but there is still work to be done.


##### scheduler Vs Orchestrator
The term "scheduler" and "orchestrator" are often used interchangeably.
In most cases, the orchestrator is responsible for all resource utilization 
in a cluster( e.g. storage, network, and CPU). The term is typically used to
describe products that do many tasks, such as health checks and cloud automation.

Schedulers are subset of orchestration platforms and are responsible only for
picking which processes and services run on each server.

* What is Cluster?

