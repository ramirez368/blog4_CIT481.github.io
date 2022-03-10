---
layout: default
---


## The Difference Between two giants in the cloud: AWS and Azure [](https://www.youtube.com/watch?v=xCabPpcq8Ac)

[//]: #  There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

## What is Azure?
Azure is an open source and flexible cloud platform which helps in development, service hosting, service management, and data storage. The Azure cloud computing tool hosts web applications over the internet with the help of Microsoft data centers.

## What is Aws?
Amazon Web Services (AWS) is widely used secure cloud services platform, offering computing power, content delivery, database storage, and other functionality to help businesses scale and grow.

## Amazon Web Services vs Microsoft Azure Features Comparison
Comparing the AWS and Azure cloud platforms is no simple task. As traditional systems have moved from on-premises to cloud, both providers have expanded their service offerings to include over 25 different cloud solution categories.

Today, AWS and Microsoft Azure offer hundreds of competitive cloud solutions encompassing countless products and services. There is a wealth of choice with categories spanning compute, storage, database, security, robotics, machine learning, and even quantum technologies. To avoid getting lost in the details while comparing apples to apples, you’ll need a basic level of knowledge and understanding of the two technologies.

Thankfully, products and services from the Amazon Web Services Platform and Microsoft Azure Platform are mostly grouped under the same category headings. To help you accelerate and simplify the decision-making process, we’ve taken the time to compare the most commonly sought-after cloud products and services across several business-critical categories.

As experts in delivering our clients market-leading WordPress hosting solutions, we have first-hand experience using these types of cloud services. On top of discussing building a cloud deployment, we’ll also take a detailed look at the key considerations that accompany these services, like customer support, global infrastructure, billing, and pricing structures.

## Compute Features
Compute resource is the foundation on which you’d build your cloud deployment. The decisions you make in this category will directly influence the speed and performance of your platform. Including the systems you run on it and the services your employees utilize. So, you must choose the right configuration for your business needs.

You also need to factor in compute cost, as it forms two-thirds of the average enterprise cloud spend, according to ParkMyCloud CEO, Jay Chapel.

Comparing Amazon Web Services vs Microsoft Azure compute capabilities, we are focused primarily on virtual machines (VMs). Forming your cloud environment’s backbone, VMs emulate physical computer systems’ functionality and power almost any workload you can think of.

Both AWS and Azure adopt a similar approach to VMs. However, as you dig into two services, you’ll discover they use different terminology for their individual compute offerings.

Amazon Web Services compute offering is known as Amazon Elastic Compute Cloud (Amazon EC2). Microsoft, on the other hand, refers to its compute product as Azure Virtual Machines. The table below maps key compute differences between AWS and Azure:

## Feature	Amazon EC2	Azure
Virtual machines	Instances	Virtual machines
Images	Amazon Machine Image	VM Image (both boot-disk-only and full machine)
VM templates	AWS Cloud Formation	Azure Resource Manager
Automatic instance scaling	Auto Scaling	Azure Autoscale
Supported VM import formats	RAW, OVA, VMDK, and VHD	VHD
Deployment locality	Zonal	Regional (equivalent to Cloud Platform zones)
Preemptible VMs	Yes	Yes
Incremental snapshots	Yes	Yes
Virtual Machine Features
As you explore VM-instance deployments in Amazon EC2 and Azure, you’ll discover the providers share many similar—if not identical—features. These include:

The ability to use stored disk images to create instances
On-demand capabilities to launch and terminate instances
Restriction-free management of your instances
The ability to tag your instances
A variety of available operating systems to install on your instance
Virtual Machine Access
You’ll find that both Azure and AWS adopt a similar approach to VM access of Linux and Windows machines.

For Linux machines, if you want SSH-based terminal access, Amazon EC2 and Azure both require you to include your own key SSH key. In addition to this, neither provider supports SSH browser access.

When it comes to VM access for Windows machines, Amazon EC2 and Azure support access through standard Remote Desktop Protocols (RDP).

Where they do differ slightly is in the provision of additional access pathways. Azure offers additional access to Windows machines via Microsoft PowerShell, while Amazon EC2 provides additional Windows machine access through its IPv6 address and Session Manager.

Virtual Machine Instance Types
To simplify and accelerate the process of deploying your VM setup, Azure and Amazon EC2 both offer a wide range of predefined instances.

Each VM instance type is configured with a specific virtual CPU, RAM, and network components. Whether opting for Microsoft or Amazon, there are hundreds of virtual machine types available to choose from.

Both providers build flexibility into the process, allowing you to customize your configuration. You can reconfigure core elements of the predefined instance, including the number of CPUs and available RAM, giving you the power to scale your VM resource capabilities up or down to match your organization’s unique requirements.

Both providers offer extreme high-end specifications to support the most demanding workloads. They currently max out with the following specifications:

Amazon EC2 VMs scale up to 448 vCPUs and 24,576 GB of RAM
Microsoft Azure VMs scale up to 416 vCPUs and 11,400 GB of RAM
To further simplify the process, both providers group VM types into categories optimized and configured for their planned usage. These VM categorizations include general-purpose, memory-optimized, compute-optimized, storage-optimized, graphics processing (GPU), and high performance.

## Virtual Machine Images
VM images accelerate your deployment by providing a pre-configured VM setup that includes an operating system, along with the supporting server and database software. Both Azure and Amazon EC2 allow the use of machine images to create new instances.

In addition to a range of proprietary ready-made image configurations, both platforms support the use of images developed by third-party vendors, which you can access through their respective platforms, AWS Marketplace and Azure Marketplace. You also have the option to create and store your own custom images for private use.

In December 2020, AWS launched Amazon Elastic Container Registry Public (ECR Public), offering the unique capability to store, manage, share, and deploy container images for anyone to discover and download globally. Proving already popular, this is no doubt a service Azure will look to replicate in the future.

Automatic Scaling of Virtual Machine Instances
Autoscaling allows you to create and remove VM instances inline with user-defined policies. You can optimize performance, scaling compute resources up or down in real-time to meet demand. This allows you to control costs, minimizing unutilized resources, so you only pay for what you need.

Both Amazon EC2 and Azure support autoscaling, implementing it in similar ways:

AWS Auto Scaling scales instances in groups. Each group has a launch configuration to create new instances and uses your chosen scaling plan to manage the creation and removal of instances.
Azure Autoscale has a VM scale set in which instances are scaled. Instances are created or removed inline with your chosen scaling plan, referred to as an autoscaling policy.
Between the platforms, there are three autoscaling plans available: manual, dynamic, and scheduled. Amazon Auto Scaling supports all three, while Azure Autoscale only supports dynamic and scheduled autoscaling. Each plan can be defined as follows:

Manual: You can manually instruct the creation and removal of instances.
Scheduled: Instances can be scaled up or down based on a predefined schedule.
Dynamic: You can create policies to scale instances based on specific metrics such as CPU utilization or message queue length.
Temporary Virtual Machine Instances
Temporary instances are VMs that run on the cloud provider’s unused capacity. These VMs are unpredictably available, so you can reallocate their resources at any given moment. As a result, they are available at highly discounted rates, letting you unlock the power of the cloud for less.

## Temporary instances are ideal for:

Workloads that can be interrupted without losing work
Low priority jobs that are not time-sensitive
Workloads that benefit from increased compute power when available, such as for rendering video
Both Amazon and Microsoft cloud platforms support temporary instances with similar naming conventions. The AWS service for temporary instances is Spot Instances, while the Azure service is Spot Virtual Machines (Spot VMs).

Both Azure and AWS temporary machines share a set of features that include:

The ability to control temporary instances when they are running
Limiting the instance types and machine images available, compared with on-demand instances
Accessing the same performance as on-demand instances when temporary instances are running
Temporary instances on AWS or Azure are available at a discounted rate of up to 90% compared with standard pay-as-you-go, on-demand pricing. It’s certainly worth investigating further.

## Performance
Comparing VM machine performance between Azure and AWS is no easy task. We can’t simply declare that one of these cloud providers is better than the other. There are hundreds of comparable VM instances available between AWS and Azure, with the performance scale tipping one of two ways, depending on the comparison.

A recent study from Cockroach Labs compared AWS vs Azure vs GCP CPU performance across a range of single-core and 16-core VMs. GCP came out on top in the single-core category, with performance 10% higher than AWS, with Azure coming in last. When comparing 16-core VMs, AWS came out on top with the fastest iterations per second. GCP was second, and Azure took last again.


## 


![ ](https://www.ursalink.com/en/wp-content/uploads/2019/10/5G-IoT.png)

## 


## 


```
Thank you readers, and wait for next week blog
For Contact e-mail me at ramirez368@hotmail.com

```
