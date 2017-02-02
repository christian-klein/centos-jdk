# ** CentOS with Java 8 on Docker**

## What is this?

   This docker build is a base for other containers. It is based on CentOS7 and Oracle Java 8

	Maintained and authored by: Christian Klein @ Base22
	
## How does it work?

1. Go to your build folder containing the Docker build files from this project.

2. Build the container:

   `docker build -t rohirrim70/centos-jdk -f jdk-Docker.build .`

3. Start the container:

   `docker run -h rohirrim70/CentOSJava`

You can now push your instance into your private repository on Docker-Hub or a repository you run yourself.

## Technical Details:

   + Current version level is:

     * CentOS 7
     * Java 8.0.112
