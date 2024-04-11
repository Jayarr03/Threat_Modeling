# 3_Layer_Threat_Model

## Purpose 

This model proposes a methodology for deconstructing system representation in threat models. 

## Layers

Threat models consist of three primary layers with the following considerations. 

1. Environmental Layer (What environment is this applicaiton or service hosted in?)
   
- Environmental layers can make tremendous templates to aid in further threat modeling scale because they could be the backbone of each an every threat model since all items exist in some environment.
- It is possible that if an organization maintains several threat models, they could pursue a single enviornmental threat model and then only add incremental threats to infrastructure in future layers.
- Example: Applicatio is hosted in AWS, GCP, or Azure


2. Infrastructure Layer (What type of infrastructure is used within this environment?)

- Infrastruture layer includes components which provide the technical capability of the services or functions of this application or system.
- Templates in this layer could include practical groupings or approved architectural representations for 3 tier web application, container services, microservices. 
- Examples: Firewall, Load Balancer, Microsoft Entra, S3 Bucket


3. Functional Layer (What fuction does this system provide?)

- Functional layer includes the key functions that differentiate this system from any other system of similiar infrastructure and environment
- Template in this layer are more complex because the functions and functional requirements are very high
- Examples: FIle Processing for new patient, processing of financial data, login process

Examples are provided in this directory which demonstrate how those threat model layers might look. 
