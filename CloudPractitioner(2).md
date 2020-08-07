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














