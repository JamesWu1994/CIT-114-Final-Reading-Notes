# CIT-114-Final-Reading-Notes
## Cloud Concepts and Overview
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
