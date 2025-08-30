1)AWS cloud watch looks for activities taking place on the AWS Cloud

2)AWS Cloud watch acts as a Gatekeeper, Watchmen for an AWS Account.

3)AWS cloud watch service watch for AWS services such as creating EC2 instances, uploading content to S3 buckets, Creating and dealing with any resource on AWS cloud.

4)AWS cloud watch helps in monitoring, Alerting, Reporting and Logging. 

5)Using these features AWS cloud watch keeps track of activities taking place on a AWS account. 

6)Monitoring: AWS cloud watch monitors AWS infrastructure and Application deployed on AWS cloud. 

7)It also helps in getting real life metrics on a AWS account. Ex: How many API requests are received by the application deployed on EC2 instance. What was the CPU utilization, memory consumption on AWS EC2 instance in last 30 minutes. 
Real life metrics helps to understand the details of AWS services. 

8)Alarms: Metrics and Alarm are closely related to each other. If CPU utilization reached 80%, then slack notifications will be send to the team. 

9)Logging: This feature of AWS cloud watch gives us Log insights. It helps us to know which AWS services are communicating with each other. 
Ex: While executing AWS CICD pipeline, AWS EC2 was communicating with AWS code deploy service.

10)Custom Metrics: AWS cloud watch tracks the CPU utilization by default. But it do not track the memory utilization out of the box. Hence using custom metrics we can send metrics for memory utilization to the AWS cloud watch service. So one can set up alarms to send notifications when memory utilization reaches threshold value. 

11)By integrating Cloud watch with Lambda functions, it also helps in Cloud Cost Optimization.

12)Scaling: By Integrating Cloud watch with Autoscaling Group, When CPU utilization reaches 80% threshold value , It will notify Auto scaling group to increase the instance count.  
