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
![[Pasted image 20250602221906.png]]

# AWS Services using PoPs
- Amazon Cloudfront
	- Content Delivery Network service
- Amazon S3 Transfer Acceleration
- AWS Global Accelerator
# AWS Direct Connect
- Private 