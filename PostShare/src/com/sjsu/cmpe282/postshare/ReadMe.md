# PostShare

PostShare is a webapp that provides the platform where users can

  - share the post
  - categorize their post based on topics
  - view the posts shared by others
  - up-vote/down-vote the posts of other users

Main focus:
  - Utilize the available cloud features to provide high availability and scalability
  - Implement RESTful webservices based micro-service archituecture using Java

### Tech

PostShare uses following technologies to work properly:

* [Apache Cassandra] - NoSQL for storing the data!
* [Spring Boot] - For developing API gateway that exposes REST Endpoints For various Functionalities
* [Docker] - Individual containers for various services
* [Amazon EC2] - Hosting the docker on cloud
* [NGINX] - URL based routing of webservices
* [AWS- ELB] - Load balancing between EC2 instances

And a link to the presentation slides of this project https://goo.gl/NiDMaV
