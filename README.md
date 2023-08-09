# Summary of AWS Well-Architected Framework

Key concepts, design principles, and architectural best practices for designing and running workloads in the cloud.

## The Six Well-Architected Pillars

### Operational Excellence Pillar

Focuses on running and monitoring systems, and continually improving processes and procedures.

#### Design principles

* Perform operations as code
* Make frequent, small, reversible changes
* Refine operations procedures frequently
* Anticipate failure
* Learn from all operational failures

#### Best practice areas

##### Organization
Your organization's priorities, structure and how it supports team members.

##### Prepare
Understand your workloads and their expected behaviors.

##### Operate
Understand the health of your workload and operations so you can respond to risks.

##### Evolve
Implement frequent small incremental changes based on the lessons learned from your operations activities and evaluate their success at bringing about improvement.

### Security Pillar

Focuses on protecting information and systems.

#### Design principles

* Implement a strong identity foundation
* Maintain traceability
* Automate security best practices
* Protect data in transit and at rest
* Keep people away from data
* Prepare for security events

#### Best practice areas

##### Security Foundations

##### Identity and access management
Set robust identity management and permissions in place to ensure that the right people have access to the right resources under the right conditions.

##### Detection
Detection of unexpected or unwanted configuration changes, and of unexpected behavior.

##### Infrastructure protection
Control methodologies, such as defense in depth, that are necessary to meet best practices and organizational or regulatory obligations.

#### Data protection
Foundational practices that influence security should be in place before architecting any workload.

#### Incident response
Implement mechanisms to respond to and mitigate the potential impact of security incidents.

#### Application security
Design, build, and test the security properties of the workloads you develop

### Reliability Pillar

Focuses on workloads performing their intended functions and how to recover quickly from failure to meet demands.

#### Design principles

* Automatically recover from failure
* Test recovery procedures
* Scale horizontally to increase aggregate workload availability
* Stop guessing capacity
* Manage change through automation

#### Best practice areas

##### Reliability Foundations
* Manage service quotas and constraints
* Plan your network topology

##### Workload architecture
* Design your workload service architecture
* Design interactions in a distributed system to prevent failures
* Design interactions in a distributed system to mitigate or withstand failures

##### Change Management
* Monitor workload resources
* Design your workload to adapt to changes in demand
* Implement change

##### Failure Management
* Back up data
* Use fault isolation to protect your workload
* Design your workload to withstand component failures
* Test reliability
* Plan for Disaster Recovery (DR)



### Performance Efficiency Pillar

Focuses on structured and streamlined allocation of IT and computing resources.

### Cost Optimization Pillar

Focuses on avoiding unnecessary costs.

### Sustainability Pillar

Focuses on minimizing the environmental impacts of running cloud workloads.

## Well-Architected Lenses

Extend the guidance offered by AWS Well-Architected to specific industry and technology domains

### SaaS Lens

### IoT Lens

#### IoT Lens Checklist

### Data Analytics Lens

### Healthcare Industry Lens

### Container Build Lens

### Serverless Applications Lens

### Hybrid Networking Lens

### Games Industry Lens

### SAP Lens

### Streaming Media Lens

### Financial Services Industry Lens

### HPC Lens
