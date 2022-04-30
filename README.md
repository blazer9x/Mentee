# MyMentor and MyMentee
Explanations


Services used are ALB (LoadBalancers), TG (TargetGroups), SG (Security Groups) - marked as red-dash square, ECS, Elastic-Container, ElasticRegistry, AWS Code Build, RDS, and AWS S3-Storage (Intelligent Tier and Glacier).


ALB is used for LoadBalancing the User Requests.

TG are used for distinc user requests based on application path (ex: example.com/mymentor or example.com/mymentee).


MyMentor and MyMentee Apps used the ECS services for Scalability and Relibility.

AWS Code Builds, Container Registry and Elastic Container Services will be use for Update and Running Containers.

*we can use Fargate to monitors jobs and config.


S3 is used to store content by the Mentor apps, while Mentee apps will can be used for getting the recorded videos.

S3 Intelligent Tiers provides cheaper S3 storage.

further cost reductions S3 Glacier will be used (for storing the old videos).

