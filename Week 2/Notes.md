## Week 2
**Cloud Service Models**
1. SaaS (most easiest, less complexity)
  - you do not care, call a *taxi*
  - In the SaaS model, in addition to the infrastructure and the platform resources, the provider also hosts and manages the applications and data.
2. PaaS
  - *rented car*, care for gas and specifications
  - With PaaS, the provider, in addition to the computing resources, also manages the platform infrastructure which includes the operating systems, development tools, databases, and business analytics.
3. SaaS (most complex, hardest)
  - *buy car* car for performance, color, gas, as well as specifications.
  - With IaaS, the cloud provider manages the physical resources, data centers, cooling power, Network and security, as well as computing resources that include servers and storage.
---
**IaaS**
It is a form of cloud computing that delivers fundamental compute, network, and storage resources to consumers on-demand, over the internet, on a pay-as-you-go basis. The cloud provider hosts the infrastructure components traditionally present in an on-premises data center as well as the virtualization or hypervisor layer.

**Virtual Machine** contains hypervisor, OS for data applications, middleware
**Storage** for backup and workloads

1. Physical data centers (physical machines)
2. Compute (compute memory storage)
3. Network (virtualization and APIs)
4. Storage (object, file, block)

**Provides**
1. test-and-development
2. business continuity and disaster recovery
3. faster development and scaling
4. high performance computing
5. big data analysis

**Concerns**
1. lack of transparency
2. dependence on a third-party

**PaaS**
Platform-as-a-Service, commonly referred to as “PaaS” or simply "pass", is a a cloud computing model that provides customers a complete platform to develop, deploy manage, and run applications created by them or acquired from a third-party. The PaaS provider hosts everything—servers, networks, storage, operating system, application runtimes, APIs, middleware, databases, and other tools at their data center. The provider also takes responsibility for the installation, configuration, and operation of the application infrastructure, leaving the user responsible for only the application code and its maintenance.
Users only need to manage for application code and data
**Essentials characteristics** include high level of abstraction, support services and APIs, run-time environments, rapid deployment mechanisms, and middleware capabilities
Uses cases include, API development and management, Internet of Things (IoT), Business Analytics/intelligence, Business Process Management (BPM), and Master data management (MDM)
Advantages include scalability, faster time to market, and greater agility and innovation
Risks include information security threats, dependency on service provider's infrastructure, customers lack control over changes in strategy, service offerings, or tools.

**SaaS**
Software-as-a-Service, “SaaS”, is a cloud offering that provides users with access to a service provider’s cloud-based software. SaaS providers maintain the servers, databases, and code that constitute an application. They also manage access to the application, including security, availability, and performance. Applications reside on a remote cloud network, and users use these applications without having to maintain and update the infrastructure.
It supports email and collaboration, customer relationship management, human resource management, financial management.
Key characteristics include multitenant architecture, manage privileges and monitor data, security, compliance, maintenance, customize application, subscription model, scalable resources.
Its benefit include greatly reduce the time from decision to value, increase workforce productivity and efficiency, and spread out software cots over time
Concerns are dependency on data-connectivity, and data ownership and data safety.
---

Cloud computing allows us to utilize technology as a service, leveraging remote resources on-demand, on a pay-as-you-model. There are three main service models available on the cloud—Infrastructure-as-a-Service (IaaS), Platform-as-a-Service (PaaS), and Software-as-a-Service (SaaS).

IaaS provides the fundamental compute, network, and storage resources for customers on-demand.

PaaS provides customers the hardware, software, and infrastructure to develop, deploy, manage, and run applications created by them or acquired from a third-party.

SaaS provides access to users to a service provider’s cloud-based software. Users simply access the applications on Cloud while the Cloud provider maintains the infrastructure, platform, data, application code, security, availability, and performance of the application.
---
**Cloud Deployment**
Deployment models indicates where the infrastructure resides, who owns and manages it, and how cloud resources and services are made.
**Public** users use servers, storage, network, security, and applications own by the provider like you use electricity, water, and gas. It is cost-effective. Its characteristics include virtualized multi-tenant architecture enabling tenants or users to share computing resources. Resources are distributed on an as-needed bases offered through a variety of subscription and pay-as-you-go models. The benefits include on-demand resources, economies of scale, highly reliable. Concerns include security and data sovereignty compliance. Organizations are increasingly opting to access cloud-based applications and platforms so their teams can focus on building and testing applications, and reducing time-to-market for their products and services. Businesses with **fluctuating capacity and resourcing needs** are opting for the public cloud. Organizations are using public cloud computing resources to build secondary infrastructures for **disaster recovery, data protection, and business continuity**. More and more organizations are using cloud storage and data management services **for greater accessibility, easy distribution, and backing up their data**. IT departments are outsourcing the management of less critical and standardized business platforms and applications to pubic cloud providers.
**Private Cloud**
The National Institute of Standards and Technology defines Private Cloud as cloud infrastructure provisioned for exclusive use by a single organization comprising multiple consumers, such as the business units within the organization. It may be owned, managed, and operated by the organization, a third party, or some combination of them, and it may exist on or off premises. It can be implemented by internal or external infrastructure. Internal infrastructure runs on-premises; owned and managed by organization. External infrastructure is owned, managed, and operated by service provider. Virtual Private Cloud (VPC) is an external cloud that offers a private, secure, computing environment in a shared public cloud. Its benefits include it is controlled by internal IT, reduced cost, better scalability, greater access and greater agility

**Hybrid Cloud**
Hybrid Cloud is a computing environment that connects an organization's on-premise private cloud and third-party public cloud into a single flexible infrastructure for running the organization's applications and workloads. The mix of public and private cloud resources gives organizations the flexibility to choose the optimal cloud for each application or workload, workloads move freely between the two clouds as needs change. Organizations can choose to run the sensitive highly regulated and mission-critical applications or workloads with reasonably constant performance and capacity requirements on private Cloud infrastructure. While deploying the less sensitive and more dynamic workloads on the public cloud. With proper integration and orchestration between the public and private clouds, you can leverage both clouds for the same workload. For example, you can leverage additional public cloud capacity to accommodate a spike in demand for a private cloud application also known as cloud bursting. The key tenants of a hybrid cloud are interoperability, scalability and portability. Hybrid cloud is interoperable, which means, that the public and private cloud services can understand each other's APIs, configuration, data formats, and forms of authentication and authorization. When there is a spike in demand a workload running on the private cloud can leverage the additional public cloud capacity making it scalable. A hybrid cloud is also portable, since you're no longer locked in with a specific vendor, you can move applications and data not just between on-premise and cloud systems, but also between cloud service providers. Hybrid is about taking the best of both worlds. There are two common types of hybrid clouds, hybrid monocloud and hybrid multi-cloud. A Hybrid Monocloud is a hybrid cloud with one cloud provider, while a Hybrid Multicloud is an open standards-based stack that can be deployed on any public cloud infrastructure. The difference lies in the flexibility that the hybrid multicloud offers organizations to move workloads and environments from one vendor to another. There is also a and of hybrid multicloud called the, Composite Multicloud, which makes this flexibility even more granular as it distributes single applications across multiple providers, allowing you to move application components across cloud services and vendors as needed. Hybrid cloud offers significant benefits in areas of security and compliance, scalability and resilience, resource optimization, and cost saving. A hybrid cloud lets organizations deploy highly regulated or sensitive workloads in a private cloud while running the less-sensitive workloads on a public cloud. Using a hybrid cloud you can scale up quickly, inexpensively, and even automatically using the public cloud infrastructure, all without impacting the other workloads running on your private cloud. Because you're not locked-in with a specific vendor and also don't have to make either-or decisions between the different cloud models, you can make the most cost-efficient use of your infrastructure budget. You can maintain workloads where they are most efficient, spin-up environments using pay-as-you-go in public cloud, and rapidly adopt new tools as you need them. A typical organization will have a range of applications and workloads spread across private public and traditional IT environments. This represents a range of opportunities for optimization via a hybrid cloud approach. Software-as-a-Service integration, through hybrid integration organizations are connecting software-as-a-service applications available in the public cloud to their existing public cloud, private cloud, and traditional IT applications to deliver new solutions. Data and AI integration, organizations today are creating richer and more personal experiences by combining new data sources on the public cloud. Such as weather, social, the Internet of things, CRM, and ERP, with existing data in analytics, machine learning, and AI capabilities. Enhancing legacy apps, an increasing number of organizations are using public cloud services to upgrade their user experience of their on-premises applications and deploy them globally to new devices, while incrementally modernizing their Core Business Systems. VM ware migration, more and more organizations are lifting and shifting their on-premises virtualized workloads to a public cloud without conversion or modification to reduce their on-premises data center footprint and position themselves to scale without added capital expense. Hybrid cloud is a concept that's been around for quite some time, but we're finding that it's becoming increasingly used to architect and modernize existing or legacy applications. According to research we found that 75% of non-cloud applications will be moving to the cloud in the next three years. This goes to say that if you're not already thinking about your hybrid cloud strategy, you may be falling behind.
---
Deployment models indicate where the infrastructure resides, who owns and manages it, and how cloud resources and services are made available to users. There are three main deployment models available on the cloud—Public, Private, and Hybrid.

In the Public cloud model, the service provider owns, manages, provisions, and maintains the physical infrastructure such as data centers, servers, networking equipment, and storage, with users accessing virtualized compute, networking and storage resources as services.

In the Private cloud model, the provider provisions the cloud infrastructure for exclusive use by a single organization. The private cloud infrastructure can be internal to the organization and run or on-premises. Or, it can be on a public cloud, as in case of Virtual Private Clouds (VPC) and be owned, managed, and operated by the cloud provider.

In the Hybrid cloud model, an organization’s on-premise private cloud and third-party, public cloud is connected as a single, flexible infrastructure leveraging the features and benefits of both Public and Private clouds.
