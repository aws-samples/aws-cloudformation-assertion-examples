## How to do cross parameter validation using CloudFormation Rules and Assertions

This code gives you some examples of how you can use CloudFormation Assertions to perform cross-parameter validations. For example, you have code snippets that validate the certificateARN parameter only if a secure listener is required as Application Load Balancer configuration. Likewise, a Hosted Zone name is expected only if a secure listener is chosen. This CloudFormation creates an entire topology with an Auto Scaling group behind a load balancer with a simple health check. The web site is available on port 80 or 443 based on the input.  however, the instances can be configured to listen on any port (8888 by default). **WARNING** This template creates one or more Amazon EC2 instances and an Application Load Balancer. You will be billed for the AWS resources used if you create a stack from this template.


## License Summary

This sample code is made available under a modified MIT license. See the LICENSE file.
