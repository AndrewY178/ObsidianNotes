## **What is AWS Global infrastructure**
- Globally distributed hardware and datacenter
- Physically networked together to act as one large resource 
- **32** Launched Regions
- **102** Availability Zones
- **115** Direct Connection Locations
- **550**+ Points of Presence
- **35** Local Zone
- **29** Wavelength Zones

# Regions
- Each region has three availability zones

Global Services
- Amazon S3
- Cloudfront
- IAM
- Route53

# Fault Tolerance
- Fault domain: section of a network that is vulnerable to damage if a critical system or device fails
- Failure is only in the domain it fails in
- Fault level: collection of fault domains
- Failure Zones: AWS describing a fault domain

# AWS Global Network
- interconnection between AWS Global Infrastructure
- Edge Locations: on and off ramps
# Point of Presence (PoP)
- data center used for content delivery or expediated upload
- Pop Resources:
	- Edge location
		- data centers that hold cached on the most popular files
	- Regional Edge cache
		- datacenters that hold much larger cache of less popular files to reduce a full round trip
# AWS Services using PoPs
- Amazon Cloudfront
	- Content Delivery Network service
- Amazon S3 Transfer Acceleration
- AWS Global Accelerator
# AWS Direct Connect
- Private/dedicated connections between your data center, office, co-location, and AWS
- Two fast network connection options
	- Lower bandwidths: 50 MBps - 500 MBps
	- Higher bandwidths: 1 GBps or 10 GBps
- Helps reduce network costs and increase bandwidths throughput
- Provides a more consistent network experience 
# Direct Connection Location
- establish a dedicated high speed, low latency connection from your on-premise to AWS
- Use AWS Direct Connect
# Local Zones
- Support highly demanding applications sensitive to latencies
	- Media and Entertainment
	- Electronic Design Automation
	- Ad-tech
	- Machine Learning
# Wavelength Zones
- Edge-computing on 5G network
- ultra-low latency being as close to the user
# Data Residency
- Physical or geographic location of where an organization or cloud resources reside
- Compliance Boundaries: boundaries that describe where the data and cloud resources are allowed to reside
- Data Sovereignty: jurisdictional control or legal authority that can be asserted over data because its physical location is within jurisdictional boundaries
- AWS Outpost: physical rack of servers
# AWS for Government
- AWS can be used by public sectors or organizations by meeting regulatory compliance programs along with specific governance and security controls
- AWS has a special region for US regulation called GovCloud
# GovCloud
- Federal Risk and Authorization Management Program (**FedRAMP**): US gov't wide program that provides an approach to security assessment, authorization, and continuous monitoring for cloud products and services.  
- Isolated region to run FedRAMP workload
- AWS GovCloud Regions allow customers to host sensitive unclassified Information and other types of regulated workloads
# AWS in China
- Completely isolated from AWS Global to meet regulatory compliance for Mainland China
# Sustainability
1. Renewable energy
	1. 100% renewable energy by 2025
2. Cloud Efficiency
	1. 3.6 times more energy efficient
3. Water Stewardship
# AWS Ground Station
- Lets you control satellite communications, process data, and scale operations 
- Weather forecasting, surface imaging, communications, video broadcasts
# AWS Outpost
- Rack of servers running AWS Infrastructure on your physical location
- Server rack: frame design to hold and organize IT equipment