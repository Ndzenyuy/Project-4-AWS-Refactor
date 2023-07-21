# Project 4: AWS Refactor
In project 3, I deployed the artifact on AWS using lift-and-shift migration strategy. It had as inconvenience, the cost was be relatively higher than using AWS native services. So in order to boost agility and business continuity and aswell easily add new features, scale effectively and easily, this project thereby aimed at refactoring the deployment by changing the EC2 instances running MySQL db, rabbitMQ, memcached and Tomcat into using AWS managed services such as RDS MySQL, AmazonMQ, Elasticache and Elastic Beanstalk. The Artifact was uploaded directly into Elastic Beanstalk which managed automatically the webserver as it is conceived to facilitate the deployment of such services. To further deliver our services closer to users, cloudfront was used.
## Services used
- Amazon Elastic Beanstalk
- IAM
- RDS -> MySQL
- AmazonMQ
- Elasticache ->memcached
- ELB
- Cloudfront
- Route53

## Project Architecture
