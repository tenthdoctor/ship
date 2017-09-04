
## Docker Containers Big Picture

###### Agenda
* What are Containers
* What is docker
* Preparing to Thrive in a Container World
* What kind of Work Will Containers Do
* Docker Hub and Other Container Registries
* Are Docker and Container Ready for Production and the Enterprise
* What is Container Orchestration All About

###### What are Containers
* Applications run businesses
* Applications run on servers
	* Procurement load times
	* Up-front capex
	* Ongoing opex
* Hypervisors allow multiple apps per server
* Containers has only one operating system and then apps over that
![](Docker%20Containers%20Big%20Picture/Screen%20Shot%202017-09-04%20at%2012.06.52%20PM.png)

In total

![](Docker%20Containers%20Big%20Picture/Screen%20Shot%202017-09-04%20at%2012.16.11%20PM.png)

###### Docker

* Now a major technology company with over a billion dollar evaluation and over 150m$ in funding
* Docker is open source with Apache License 2.0
* Multiple tools in the project and around them
* Core docker is written in [Golang](https://golang.org/)
* Docker project now looks like

![](Docker%20Containers%20Big%20Picture/Screen%20Shot%202017-09-04%20at%2012.27.05%20PM.png)

###### Open Container Initiative

Lightweight governance council
* Standardize
	* Container format
	* Container runtime
* Vendor neutral
* Platform neutral
Formed in June 2015
Operates under **The Linux Foundation**

###### The Container World

* Stateless app does not keep any changes or data, Stateful app remembers changes and data.
* Docker and containers can handle Stateful and Stateless workloads, however they excel in stateless apps
* A lot of early messaging for Docker Inc. was about using containers for modern cloud-native apps
	* This is where containers naturally excel
	* It does not mean that containers cannot be used for traditional enterprise apps
* Docket Containers are persistent
	* Stopping a container does not wipe its data
	* Restarting a container brings its data back
	* Container data stored in volumes persists even after the container is destroyed

###### Docker Hub and Other Container Repositories

* Places to store and retrieve container images
* Docker hub is official Docker registry
* 3rd party registries exist
* Docker hub has both public and private repositories
* Private registries are available
	* Run inside of your corporate network
	* Docker Trusted Registry
	* Quay Enterprise
* Docker Content Trust: For trusted docker images
* Container registries are becoming central to application infrastructure and application delivery

![](Docker%20Containers%20Big%20Picture/Screen%20Shot%202017-09-04%20at%203.32.24%20PM.png)

###### Containers Ready for Production?

* Three Channels
	* Experimental
		* Nightly Releases, Bleeding edge
	* Stable
		* Releases ~ Every two months
	* Commercially Supported
		* Releases ~ every six months
		* Stable configs
		* Support contract
* Docker Swarm gives native docker clustering
	* Scales very well
* Docker Content Trust adds trust
	* Verify content and publisher
* Docker offers both cloud on on-premise deployment

![](Docker%20Containers%20Big%20Picture/Screen%20Shot%202017-09-04%20at%203.44.49%20PM.png)

###### Container Orchestration

* Apps comprise multiple parts
	* Thousands of containers
	* Hundreds of hosts

![](Docker%20Containers%20Big%20Picture/Screen%20Shot%202017-09-04%20at%204.00.07%20PM.png)

* Orchestration
	* Defines our app
	* Provisions infrastructure
	* Deploys our app
	* Scales our app
* Docker orchestration products: Machine, Compose, Swarm

![](Docker%20Containers%20Big%20Picture/Screen%20Shot%202017-09-04%20at%204.02.00%20PM.png)

* There are many orchestrators

![](Docker%20Containers%20Big%20Picture/Screen%20Shot%202017-09-04%20at%204.02.23%20PM.png)


##### References

[8 surprising facts about real Docker adoption](https://www.datadoghq.com/docker-adoption/)





