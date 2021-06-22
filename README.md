# Practice Exam
https://www.udemy.com/course/aws-certified-developer-associate-practice-tests-dva-c01/?couponCode=MAY_21_GET_STARTED
# Code
https://media.datacumulus.com/aws-dva/code.zip 

# Slids
https://media.datacumulus.com/aws-dva/AWS%20Certified%20Developer%20Slides%20v4.0.pdf

# AWS Infrastructure
## Regions
- AWS has the concept of a Region, which is a physical location around the world where we cluster data centers. 
- We call each group of logical data centers an Availability Zone. 
## Availability Zone (AZ)
- An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region. 
- AZs give customers the ability to operate production applications and databases that are more highly available, fault tolerant, and scalable than would be possible from a single data center. 
- All AZs in an AWS Region are interconnected with high-bandwidth, low-latency networking, over fully redundant, dedicated metro fiber providing high-throughput, low-latency networking between AZs. 
- All traffic between AZs is encrypted. 
- The network performance is sufficient to accomplish synchronous replication between AZs. 
- AZs make partitioning applications for high availability easy. 
- If an application is partitioned across AZs, companies are better isolated and protected from issues such as power outages, lightning strikes, tornadoes, earthquakes, and more. 
- AZs are physically separated by a meaningful distance, many kilometers, from any other AZ, although all are within 100 km (60 miles) of each other.

## AWS Local Zones
- AWS Local Zones place compute, storage, database, and other select AWS services closer to end-users. 
- With AWS Local Zones, you can easily run highly-demanding applications that require single-digit millisecond latencies to your end-users such as media & entertainment content creation, real-time gaming, reservoir simulations, electronic design automation, and machine learning.
- Each AWS Local Zone location is an extension of an AWS Region where you can run your latency sensitive applications using AWS services such as Amazon Elastic Compute Cloud, Amazon Virtual Private Cloud, Amazon Elastic Block Store, Amazon File Storage, and Amazon Elastic Load Balancing in geographic proximity to end-users. 
- AWS Local Zones provide a high-bandwidth, secure connection between local workloads and those running in the AWS Region, allowing you to seamlessly connect to the full range of in-region services through the same APIs and tool sets.
## AWS Weavelength
- AWS Wavelength enables developers to build applications that deliver single-digit millisecond latencies to mobile devices and end-users. 
- AWS developers can deploy their applications to Wavelength Zones, AWS infrastructure deployments that embed AWS compute and storage services within the telecommunications providers’ datacenters at the edge of the 5G networks, and seamlessly access the breadth of AWS services in the region. 
- This enables developers to deliver applications that require single-digit millisecond latencies such as game and live video streaming, machine learning inference at the edge, and augmented and virtual reality (AR/VR). 
- AWS Wavelength brings AWS services to the edge of the 5G network, minimizing the latency to connect to an application from a mobile device. 
- Application traffic can reach application servers running in Wavelength Zones without leaving the mobile provider’s network. 
- This reduces the extra network hops to the Internet that can result in latencies of more than 100 milliseconds, preventing customers from taking full advantage of the bandwidth and latency advancements of 5G.
## AWS Outpost
- AWS Outposts bring native AWS services, infrastructure, and operating models to virtually any data center, co-location space, or on-premises facility. 
- You can use the same AWS APIs, tools, and infrastructure across on-premises and the AWS cloud to deliver a truly consistent hybrid experience. 
- AWS Outposts is designed for connected environments and can be used to support workloads that need to remain on-premises due to low latency or local data processing needs.
## AWS GovCloud (US)
# Global Infrastructure
https://aws.amazon.com/about-aws/global-infrastructure/
## AWS Service list
https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/?p=ngi&loc=4

# IAM
https://308784365753.signin.aws.amazon.com/console
https://dilip-2021.signin.aws.amazon.com/console

## How to access AWS?
- AWS Management Console (protected by password + MFA)
- AWS Command Line Interface or CLI (protected by access key)
- AWS Software Development Kit  SDK (for code, protected by access key)
# AWS CLI
# AWS ClouldShell

# EC2 Instances
https://instances.vantage.sh/
