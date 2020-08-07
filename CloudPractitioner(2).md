## Cloud Computing
Years back, the data base and other services required for computing, hosting and storage were on prem. Companies relied on physical on prem facilities for this. With advent of `Cloud Computing`, these service are available via internet or in other words made virtually available. Now there are companies that offer these features as services. They have data centers across the globe, 24*7 operational and secure. The serives can be accessed via internet.

### Merits
1. More elastic: Scaling up and scaling down is easier as per changing requirements.
2. Agile: Fast patching, rolling updates and deployment.
3. Secure: The data is so secured and disaster prone.
4. Wider reach: For fater delivery we need the data centers to be as closest as possible to the user. Most of the service provides have their data centers all over the global, so we can ensure faster delivery to all of our customers across the globe.
5. Cost efficient: As we make optimum use of resources with auto scale, and lesser maintenance and operational costs, monetary wise it is beneficial.
6. Innivation: With pluggable resources, innovations are easy and hussle free. 

## AWS
We can access AWS resources and services via:
1. AWS console
2. AWS CLI
3. AWS SDks

AWS has data centers across the globe(Regions). They have AZ(Availability Zones), which are indivial data centers with its own power and backups, and well separated but interconnected. So a Region can have multiple AZs within it.

#### Resource
It is group or collection of services that the user create for ease of use and accessibility. The resources can be shared among other users in the organisation.

## AWS EC2 Instance
- Pay as you go
- Only charged for running instances and time

### Nomenclature 
- Instance type: Hardware Requirements
- Amazon Machine Image: Software details
- Tags: user defined identifiers
- Security Group: firewall rules to control access and traffic to the instance

### Connection
To connect to the instance from Terminal
`sudo ssh -i pem_file_path ec2-user@instance_public_dns`

## Elastic Block Store
These store type that we can plug to EC2. They are of two type:
- SSD
- Magnetic (HDD)

_They must be in the same region as the EC2 instance to which we want to hook it._


## AWS Simple Storage Service (S3)
- A cloud storage service
- Things are stored as objects, the file name being the key and the file as the value.
- Auto scaled
- Files can be uploaded and downloaded via APIs
- The collections are called Buckets.
- We add the files into the bucket and we get a URL for the file. `https://bucket_name.region.amazonaws.com/file_name.extension`
- We can control the access to the bucket by specifying rules.

## AWS Global Infrastructure 

### Region
Regions are a group of one or more AZs,

### Availability Zones
Physically and Logically distinct data centers, with their own power backups. They are interconnected with a low latency network. 

### Edge Locations
For faster context delivery the content is served from the nearest edge location(CDN and CloudFront)

## Virtual Private Cloud (VPC)
Each organisations might have their own networking practices and security policies to adhere to. VPCs are for such kind of use cases. In a VPC the creator gets the complete freedom to configure and setup the network configuration and security layers. They can control all the traffic. VPC can span across multiple AZs. Within a VPC we can create _Subnets_ which can either be connected to internet(pulic) or not(private). For communication btw the subnets and to the outside world we can maintain routing tables.


## Security Groups
This are like in-built firewalls. Users can set the access control and traffic using the security groups.












