# Summary of AWS Well-Architected Framework

Key concepts, design principles, and architectural best practices for designing and running workloads in the cloud.

## The Six Well-Architected Pillars

### Operational Excellence Pillar

A commitment to build software correctly while consistently delivering a great customer experience.
Focuses on running and monitoring systems, and continually improving processes and procedures.

#### Design principles

* Perform operations as code
* Make frequent, small, reversible changes
* Refine operations procedures frequently
* Anticipate failure
* Learn from all operational failures

#### Best practice areas

##### Organization
* Your teams need to have a shared understanding of your entire workload, their role in it, and shared business goals to set the priorities that will create business success.
* Teams need to understand their roles in the success of other teams, the role of other teams in their success, and have shared goals.
* Provide support for your team members so that they can be more effective in taking action and supporting your business outcome.

##### Prepare
* Design telemetry. Design your workload so that it provides the information necessary for you to understand its internal state (for example, metrics, logs, events, and traces) across all components in support of observability and investigating issues.
* Design for operations. Adopt approaches that improve the flow of changes into production and that help refactoring, fast feedback on quality, and bug fixing.
* Mitigate deployment risks. Adopt approaches that provide fast feedback on quality and provide rapid recovery from changes that do not have desired outcomes.
* Operational readiness and change management. Evaluate the operational readiness of your workload, processes, procedures, and personnel to understand the operational risks related to your workload.

##### Operate
Define, capture, and analyze operations metrics to gain visibility to workload events so that you can take appropriate action.
* Understanding workload health.
* Understanding operational health.
  
##### Evolve
* Learn, share, and improve. Implement frequent small incremental changes based on the lessons learned from your operations activities and evaluate their success at bringing about improvement.

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
* Shared responsibility
* AWS response to abuse and compromise
* Governance. Upport business objectives by defining policies and control objectives to help manage risk.

##### Identity and access management
Ensure that the right people have access to the right resources under the right conditions.
* Identity management
* Permissions management

##### Detection
Detection of unexpected or unwanted configuration changes, and of unexpected behavior.

##### Infrastructure protection
Control methodologies, such as defense in depth, that are necessary to meet best practices and organizational or regulatory obligations.
* Protecting networks
* Protecting compute

#### Data protection
Before architecting any workload, foundational practices that influence security should be in place.
* Data classification
* Protecting data at rest
* Protecting data in transit

#### Incident response
Implement mechanisms to respond to and mitigate the potential impact of security incidents.
* Evaluate design goals of cloud response
* Educate
* Prepare
* Simulate
* Iterate

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

##### Foundations
* Manage service quotas and constraints
* Plan your network topology

##### Workload architecture
* Build highly scalable and reliable workloads using a service-oriented architecture (SOA) or a microservices architecture.
* Design interactions in a distributed system to prevent failures
* Design interactions in a distributed system to mitigate or withstand failures

##### Change management
* Monitor workload resources
* Design your workload to adapt to changes in demand
* Implement change

##### Failure management
* Back up data
* Use fault isolation to protect your workload
* Design your workload to withstand component failures
* Test reliability
* Plan for Disaster Recovery (DR)

### Performance Efficiency Pillar

Focuses on structured and streamlined allocation of IT and computing resources.

#### Design principles
* Democratize advanced technologies
* Go global in minutes
* Use serverless architectures
* Experiment more often
* Consider mechanical sympathy

#### Best practice areas

  


### Cost Optimization Pillar

Focuses on avoiding unnecessary costs.

#### Design principles

#### Best practice areas

### Sustainability Pillar

Focuses on minimizing the environmental impacts of running cloud workloads.

#### Design principles

#### Best practice areas

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
