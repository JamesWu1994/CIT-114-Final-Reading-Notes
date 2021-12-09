# CIT-114-Final-Reading-Notes
# Cloud Concepts and Overview
* A cloud refers to a distinct IT environment that is designed for the purpose of remotely provisioning scalable and measured IT resources.
* The term originated as a metaphor for the Internet which is, in essence, a network of networks providing remote access to a set of decentralized IT resources.
* A cloud was commonly used to represent the Internet in a variety of specifications and mainstream documentation of Web-based architectures. 
* Much of the Internet is dedicated to the access of content-based IT resources published via the World Wide Web.
* IT resources provided by cloud environments, on the other hand, are dedicated to supplying back-end processing capabilities and user-based access to these capabilities.
* Another key distinction is that it is not necessary for clouds to be Web-based even if they are commonly based on Internet protocols and technologies.
* A cloud can be based on the use of any protocols that allow for the remote access to its IT resources.
## On-Premise
* An IT resource that is hosted in a conventional IT enterprise within an organizational boundary (that does not specifically represent a cloud) is considered to be located on the premises of the IT enterprise, or on-premise for short.
* In other words, the term "on-premise" is another way of stating "on the premises of a controlled IT environment that is not cloud-based."
* This term is used to qualify an IT resource as an alternative to "cloud-based." An IT resource that is on-premise cannot be cloud-based, and vice-versa.
* An on-premise IT resource can access and interact with a cloud-based IT resource.
* An on-premise IT resource can be moved to a cloud, thereby changing it to a cloud-based IT resource.
* Redundant deployments of an IT resource can exist in both on-premise and cloud based environments.
## Scaling
*  the ability of the IT resource to handle increased or decreased usage demands.
*  The following are types of scaling:
 * Horizontal Scaling - scaling out and scaling in
  * The allocating or releasing of IT resources that are of the same type is referred to as horizontal scaling
 * Vertical Scaling - scaling up and scaling down
  * When an existing IT resource is replaced by another with higher or lower capacity, vertical scaling is considered to have occurred
## Cloud Service
* A cloud service is any IT resource that is made remotely accessible via a cloud. Unlike other IT fields that fall under the service technology umbrella - such as service-oriented architecture - the term "service" within the context of cloud computing is especially broad.
* A cloud service can exist as a simple Web-based software program with a technical interface invoked via the use of a messaging protocol, or as a remote access point for administrative tools or larger environments and other IT resources.
## Cloud Service Consumer
* The cloud service consumer is a temporary runtime role assumed by a software program when it accesses a cloud service.
# 2.4 Goals and Benefits
## Reduced Investments and Proportional Costs
* Similar to a product wholesaler that purchases goods in bulk for lower price points, public cloud providers base their business model on the mass-acquisition of IT resources that are then made available to cloud consumers via attractively priced leasing packages.
* This opens the door for organizations to gain access to powerful infrastructure without having to purchase it themselves.
* The most common economic rationale for investing in cloud-based IT resources is in the reduction or outright elimination of up-front IT investments, namely hardware and software purchases and ownership costs.
* Common measurable beneﬁts to cloud consumers include:
 * On-demand access to pay-as-you-go computing resources on a short-term basis (such as processors by the hour), and the ability to release these computing resources when they are no longer needed.
 * The perception of having unlimited computing resources that are available on demand, thereby reducing the need to prepare for provisioning.
 * The ability to add or remove IT resources at a ﬁne-grained level, such as modifying available storage disk space by single gigabyte increments.
 * Abstraction of the infrastructure so applications are not locked into devices or locations and can be easily moved if needed.
 ## Increased Scalability
* By providing pools of IT resources, along with tools and technologies designed to leverage them collectively, clouds can instantly and dynamically allocate IT resources to cloud consumers, on-demand or via the cloud consumer's direct conﬁguration.
* This empowers cloud consumers to scale their cloud-based IT resources to accommodate processing ﬂuctuations and peaks automatically or manually.
* Similarly, cloud-based IT resources can be released (automatically or manually) as processing demands decrease.
## Increased Availability and Reliability
* The availability and reliability of IT resources are directly associated with tangible business benefits.
* Outages limit the time an IT resource can be "open for business" for its customers, thereby limiting its usage and revenue generating potential.
* Runtime failures that are not immediately corrected can have a more significant impact during high-volume usage periods.
* Not only is the IT resource unable to respond to customer requests, its unexpected failure can decrease overall customer confidence.
* An IT resource with increased availability is accessible for longer periods of time (for example, 22 hours out of a 24 hour day). Cloud providers generally offer "resilient" IT resources for which they are able to guarantee high levels of availability.
* An IT resource with increased reliability is able to better avoid and recover from exception conditions. The modular architecture of cloud environments provides extensive failover support that increases reliability.
* It is important that organizations carefully examine the Service Level Agreements (SLAs) offered by cloud providers when considering the leasing of cloud-based services and IT resources.
# 2.5 Risks and Challenges
## Increased Security Vulnerabilities
* The moving of business data to the cloud means that the responsibility over data security becomes shared with the cloud provider.
* The remote usage of IT resources requires an expansion of trust boundaries by the cloud consumer to include the external cloud.
* It can be difﬁcult to establish a security architecture that spans such a trust boundary without introducing vulnerabilities, unless cloud consumers and cloud providers happen to support the same or compatible security frameworks - which is unlikely with public clouds.
* The overlapping of trust boundaries and the increased exposure of data can provide malicious cloud consumers (human and automated) with greater opportunities to attack IT resources and steal or damage business data.
## Reduced Operational Governance Control
* Cloud consumers are usually allotted a level of governance control that is lower than that over on-premise IT resources.
* This reduced level of governance control can introduce risks associated with how the cloud provider operates its cloud, as well as the external connections that are required to communicate between the cloud and the cloud consumer.
* Legal contracts, when combined with SLAs, technology inspections, and monitoring, can mitigate governance risks and issues.
* A cloud governance system is established through SLAs, given the "as-a-service" nature of cloud computing. A cloud consumer must keep track of the actual service level being offered and the other warranties that are made by the cloud provider.
## Limited Portability Between Cloud Providers
* Due to a lack of established industry standards within the cloud computing industry, public clouds are commonly proprietary to various extents.
* For cloud consumers that have custom-built solutions with dependencies on these proprietary environments, it can be challenging to move from one cloud provider to another.
* Portability is a measure used to determine the impact of moving cloud consumer IT resources and data between clouds.
## Multi-Regional Regulatory and Legal Issues
* Third-party cloud providers will frequently establish data centers in affordable or convenient geographical locations.
* Cloud consumers will often not be aware of the physical location of their IT resources and data when hosted by public clouds.
* For some organizations, this can pose serious legal concerns pertaining to industry or government regulations that specify data privacy and storage policies. For example, some UK laws require personal data belonging to UK citizens to be kept within the United Kingdom.
* Another potential legal issue pertains to the accessibility and disclosure of data.
# Cloud Economics, Billing, and Support
# 2.2 Business Drivers
* The origins and inspirations of many of the characteristics, models, and mechanisms covered throughout subsequent chapters can be traced back to the upcoming business drivers.
## Capacity Planning
* Capacity planning is the process of determining and fulfilling future demands of an organization's IT resources, products, and services.
* Within this context, capacity represents the maximum amount of work that an IT resource is capable of delivering in a given period of time.
* A discrepancy between the capacity of an IT resource and its demand can result in a system becoming either inefficient (over-provisioning) or unable to fulfill user needs (under-provisioning).
* Seeks to minimize this discrepancy
* Different capacity planning strategies exist:
  * Lead Strategy - adding capacity to an IT resource in anticipation of demand
  * Lag Strategy - adding capacity when the IT resource reaches its full capacity
  * Match Strategy - adding IT resource capacity in small increments, as demand increases
* Planning for capacity can be challenging because it requires estimating usage load fluctuations.
* There is a constant need to balance peak usage requirements without unnecessary over-expenditure on infrastructure.
## Cost Reduction
* A direct alignment between IT costs and business performance can be difficult to maintain.
* This can make the support of new and expanded business automations an ever-increasing investment. 
* Much of this required investment is funneled into infrastructure expansion because the usage potential of a given automation solution will always be limited by the processing power of its underlying infrastructure.
* Two costs need to be accounted for:
  * The cost of acquiring new infrastructure
  * The cost of its ongoing ownership.
* Operational overhead represents a considerable share of IT budgets, often exceeding up-front investment costs.
* Common forms of infrastructure-related operating overhead include the following:
  * Technical personnel required to keep the environment operational
  * Upgrades and patches that introduce additional testing and deployment cycles
  * Utility bills and capital expense investments for power and cooling
  * Security and access control measures that need to be maintained and enforced to protect infrastructure resources
  * Administrative and accounts staff that may be required to keep track of licenses and support arrangements
 ## Organizational Agility
* Organizational agility is the measure of an organization's responsiveness to change.
* An IT enterprise often needs to respond to business change by scaling its IT resources beyond the scope of what was previously predicted or planned for.
# Cloud Global Infrastructure
# Chapter 1 The Big Picture
* Devops is a way of thinking and a way of working
* It is part of the cultural weave that shapes how we work and why
* An equally important part of our culture is our values, norms, and knowledge
* What makes tools “devops” is the manner of their use, not fundamental characteristics of the tools themselves.
* Devops is not just another software development methodology. Although it is related to and even influenced by software development methodologies like Agile or XP, and its practices can include software development methods, or features like infrastructure automation and continuous delivery, it is much more than just the sum of these parts. While these concepts are related and may be frequently seen in devops environments, focusing solely on them misses the bigger picture—the cultural and interpersonal aspects that give devops its power.

## A Snapshot of Devops Culture
* A new engineer at Etsy starts her first day with a laptop and a development virtual machine (VM) already set up with the appropriate accounts for access and authorization, the most common GitHub repositories cloned, aliases and shortcuts to relevant tools precreated, and a guide with new hire information and links to other company resources on her desktop.
* A current employee will pair with the new employee to walk through what testing and development processes she will use in her day-to-day work. She starts by writing code on her local development VM, which is set up with configuration management to be nearly identical to the live production environment.
* In Etsy’s high-trust, blameless environment, people are given the trust and authority to decide whether a code review is necessary.

## The Evolution of Culture
* This story of Etsy today is in stark contrast to how things were several years ago with a less transparent and more error-prone deployment process that took close to four hours.
* Developers had their own blade servers to work on, rather than virtual machines, but the blade servers weren’t powerful enough to run the automated test suites to completion.
* Tests that were run in the staging environment took a couple of hours to complete, and even then they were flaky enough to make their results less than useful.
* Developers had their own blade servers to work on, rather than virtual machines, but the blade servers weren’t powerful enough to run the automated test suites to completion.

## The Value of The Story
* Effective DevOps contains case studies and stories from both teams and individuals.

# Chapter 2. What Is Devops?
* Devops is a cultural movement that changes how individuals think about their work, values the diversity of work done, supports intentional processes that accelerate the rate by which businesses realize value, and measures the effect of social and technical change.
* It is a way of thinking and a way of working that enables individuals and organizations to develop and maintain sustainable work practices.

## A Prescription for Culture
* Devops is about finding ways to adapt and innovate social structure, culture, and technology together in order to work more effectively.

## The DevOps Equation
* While the term devops itself is a portmanteau of “development” and “operations,” the core concepts of devops can and should be applied throughout the entire organization.
* A sustainable, successful business is more than the development and operations teams.

## DevOps as Folk Model
* In many ways, devops has become a folk model, a term used with different intent that leads to miscommunication and misunderstanding.
* Folk models are not necessarily bad and become problematic when different groups use the same term with different intent.
* Situational awareness

## The Old View and the New View
* Old: In an environment where humans are blamed and punished for errors, a culture of fear can build up walls that prevent clear communication and transparency.
* “human error as the cause of trouble.”
* New: Contrast this with a blameless environment, where issues are addressed cooperatively and viewed as learning opportunities for individuals and the organization.
* “human error as a symptom of trouble deeper in the system.”
