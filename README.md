# Documentation1-2-3
Q2-Answer—
I would suggest to use dynamic auto scaling policy with SNS on 50-60% CPU utilisation on cloud watch service which will  scale out or scale in the instances
according to the traffic. That will scale out instances which will handle the overwhelming traffic. Also suggest to implement for better service  ALB, CDN, S3, 
ElastiCache/Redis which will reduce the traffic on the Servers.
  
Q3-Answer—
ElastiCache is a web service that makes it easy to deploy, operate and scale an in-memory cache in the cloud. It improves the performance of the web application
by allowing you to retrieve information fast, managed, in-memory caches Instead of replying entirely on slow disk-based  databases. 
       
EastiCache supports two open-source in-memory caching engines:
	1-Memcached
	2-Redis.
	
Redis support backup & Restore Capabilities, Multi AZ and use advanced data type. Able to	scale horizontally, sorting data sets also persistance
and the other hand memcached 		doesn’t support all of the above. That is why we should use Redis.  

	
I unable to test NFSLocation server that is why I unable to configure on cloud formation I apologise for that also ScaleUpCooldown and ScaleDownCooldown
not possible to configure ASG written on amazon website. 
