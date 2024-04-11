# 3_Layer_Threat_Model

## Purpose 

This model proposes a methodology for deconstructing system representation in threat models. 

## Layers

Threat models consist of three primary layers with the following considerations. 

1. Environmental Layer (What environment is this application or service hosted in?)
   
- Environmental layers can make tremendous templates to aid in further threat modeling scale because they could be the backbone of each an every threat model since all items exist in some environment.
- It is possible that if an organization maintains several threat models, they could pursue a single environmental threat model and then only add incremental threats to infrastructure in future layers.
- Example: Application is hosted in AWS, GCP, or Azure


2. Infrastructure Layer (What type of infrastructure is used within this environment?)

- Infrastructure layer includes components that provide the technical capability of the services or functions of this application or system.
- Templates in this layer could include practical groupings or approved architectural representations for 3-tier web applications, container services, and microservices. 
- Examples: Firewall, Load Balancer, Microsoft Entra, S3 Bucket


3. Functional Layer (What function does this system provide?)

- The functional layer includes the key functions that differentiate this system from any other system of similiar infrastructure and environment
- Templates in this layer are more complex because the functions and functional requirements are very high
- Examples: File Processing for new patients, processing of financial data, login process

Examples are provided in this directory which demonstrate how those threat model layers might look. 
