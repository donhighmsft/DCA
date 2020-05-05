
# Docker Certified Associate Exam Preparation Guide (v1.1)

This guide is intended to be a point of knowledge for everyone who wants to pass [Docker Certified Associate Exam](https://blog.docker.com/2017/09/introducing-docker-global-professional-certification-program/). The main idea is to provide links to every topic in each domain. Preference will always be the official documentation, but feel free to add useful links.

## Table of Contents:
1. [Orchestration](https://github.com/Evalle/DCA/blob/master/README.md#domain-1-orchestration-25-of-exam)
2. [Image Creation, Management, and Registry](https://github.com/Evalle/DCA/blob/master/README.md#domain-2-image-creation-management-and-registry-20-of-exam)
3. [Installation and Configuration](https://github.com/Evalle/DCA/blob/master/README.md#domain-3-installation-and-configuration-15-of-exam)
4. [Networking](https://github.com/Evalle/DCA/blob/master/README.md#domain-4-networking-15-of-exam)
5. [Security](https://github.com/Evalle/DCA/blob/master/README.md#domain-5-security-15-of-exam)
6. [Storage and Volumes](https://github.com/Evalle/DCA/blob/master/README.md#domain-6-storage-and-volumes-10-of-exam)
7. [Links](https://github.com/evalle/dca#links)

## Content

### Domain 1: Orchestration (25% of exam)
- [Complete the setup of a swarm mode cluster, with managers and worker nodes](https://docs.docker.com/engine/swarm/swarm-tutorial/create-swarm/)
-  [Describe and demonstrate how to extend the instructions to run individual containers into running services under swarm](https://docs.docker.com/engine/swarm/swarm-tutorial/deploy-service/)
- [Describe the importance of quorum in a swarm cluster.](https://docs.docker.com/engine/swarm/raft/)
- [Describe the difference between running a container and running a service.](https://stackoverflow.com/a/43408904)
- [Interpret the output of "docker inspect" commands](https://docs.docker.com/engine/swarm/swarm-tutorial/inspect-service/)
- [Demonstrate steps to lock a swarm cluster](https://docs.docker.com/engine/swarm/swarm_manager_locking/)

- [Convert an application deployment into a stack file using a YAML compose file with "docker stack deploy"](https://docs.docker.com/engine/swarm/stack-deploy/)
- [Manipulate a running stack of services](https://docs.docker.com/engine/reference/commandline/stack_services/#related-commands)
- [Describe and demonstrate orchestration activities.](https://docs.docker.com/get-started/orchestration/)
- [Increase number of replicas](https://docs.docker.com/engine/reference/commandline/service_scale/)
- Add networks and published ports: [Network on Swarm](https://docs.docker.com/v17.09/engine/swarm/networking/) and [network in general with published ports](https://docs.docker.com/network/)
- [Mount volumes](https://docs.docker.com/storage/volumes/)
- [Describe and demonstrate how to run replicated and global services.](https://docs.docker.com/engine/swarm/how-swarm-mode-works/services/#replicated-and-global-services)
- [Apply node labels to demonstrate placement of tasks](https://docs.docker.com/engine/reference/commandline/node_update/)
- [Describe and demonstrate how to use templates with “docker service create”.](https://docs.docker.com/engine/reference/commandline/service_create/#create-services-using-templates)
- [Identify the steps needed to troubleshoot a service not deploying](https://success.docker.com/article/swarm-troubleshooting-methodology)
- [Describe how a Dockerized application communicates with legacy systems.](https://docs.docker.com/config/containers/container-networking/)
- Describe how to deploy containerized workloads as Kubernetes [pods](https://docs.docker.com/get-started/orchestration/) and [deployments](https://docs.docker.com/get-started/kube-deploy/).
- Describe how to provide configuration to Kubernetes pods using [configMaps](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/) and [secrets](https://kubernetes.io/docs/concepts/configuration/secret/).

### Domain 2: Image Creation, Management, and Registry (20% of exam)
- [Describe the use of Dockerfile](https://docs.docker.com/engine/reference/builder/).
- [Describe Dockerfile options (add, copy, volumes, expose, entrypoint, etc)](https://docs.docker.com/engine/reference/builder/#from)
- [Identify and display the main parts of a Dockerfile.](https://docs.docker.com/engine/reference/builder/#dockerfile-examples)
- [Describe and demonstrate how to create an efficient image via a Dockerfile.](https://docs.docker.com/engine/userguide/eng-image/dockerfile_best-practices/)
- [Describe and demonstrate how to use CLI commands to manage images, such as list, delete, prune, rmi.](https://docs.docker.com/engine/reference/commandline/image/#usage)
- [Describe and demonstrate how to inspect images and report specific attributes using filter and format](https://docs.docker.com/engine/reference/commandline/inspect/#extended-description)
- [Describe and demonstrate how to tag an image.](https://docs.docker.com/engine/reference/commandline/tag/)
- [Describe and demonstrate how to apply a file to create a Docker image](https://docs.docker.com/get-started/part2/)
- [Utilize a registry to store an image](https://docs.docker.com/registry/deploying/#run-a-local-registry)
- [Describe and demonstrate how to display layers of a Docker image](https://docs.docker.com/engine/reference/commandline/image_history/)
- [Apply a file to create a Docker image](https://docs.docker.com/engine/reference/commandline/image_load/)
- [Describe and demonstrate how to modify an image to a single layer.](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/#minimize-the-number-of-layers)
- [Describe how image layers work](https://docs.docker.com/storage/storagedriver/#images-and-layers)
- [Deploy a registry (not architect)](https://docs.docker.com/registry/deploying/)
- [Configure a registry](https://docs.docker.com/registry/configuration/)
- [Log into a registry](https://docs.docker.com/engine/reference/commandline/login/#parent-command)
- [Utilize search in a registry](https://docs.docker.com/engine/reference/commandline/search/)
- [Tag an image](https://docs.docker.com/engine/reference/commandline/tag/)
- [Push an image to a registry](https://docs.docker.com/engine/reference/commandline/push/)
- [Sign an image in a registry](https://docs.docker.com/datacenter/dtr/2.4/guides/user/manage-images/sign-images/)
- [Pull an image from a registry](https://docs.docker.com/engine/reference/commandline/pull/)
- Describe how image deletion works. [Pruning](https://docs.docker.com/config/pruning/) and [removing](https://docs.docker.com/engine/reference/commandline/rmi/)
- [Delete an image from a registry](https://docs.docker.com/datacenter/dtr/2.0/repos-and-images/delete-an-image/)

### Domain 3: Installation and Configuration (15% of exam)
- [Describe sizing requirements for installation](https://docs.docker.com/datacenter/ucp/2.2/guides/admin/install/system-requirements/#hardware-and-software-requirements)
- [Demonstrate the ability to upgrade the Docker engine](https://docs.docker.com/install/linux/docker-ce/ubuntu/#upgrade-docker-engine---community)
- [Describe and demonstrate the setup of repo, selection of a storage driver, and installation of the Docker engine on multiple platforms](https://docs.docker.com/install/)
- [Describe and demonstrate configuration of logging drivers (splunk, journald, etc.).](https://docs.docker.com/config/containers/logging/configure/)
- [Describe and demonstrate how to set up swarm, configure managers, add nodes, and setup the backup schedule.](https://docs.docker.com/engine/swarm/admin_guide/)
- [Describe and demonstrate how to create and manage user and teams.](https://docs.docker.com/datacenter/dtr/2.4/guides/admin/manage-users/create-and-manage-teams/)
- [Describe and interpret errors to troubleshoot installation issues without assistance.](https://docs.docker.com/config/daemon/#troubleshoot-the-daemon)
- [Describe the use of namespaces, cgroups, and certificate configuration](https://docs.docker.com/engine/docker-overview/#namespaces)
- [Describe and demonstrate how to use certificate-based client-server authentication to ensure a Docker daemon has the rights to access images on a registry.](https://docs.docker.com/engine/security/certificates/)
- Consistently repeat steps to deploy Docker engine, UCP, and DTR on AWS and on
premises in an HA config. [Docker,](https://docs.docker.com/install/linux/docker-ce/ubuntu/) [DTR,](https://docs.docker.com/datacenter/dtr/2.3/guides/admin/install/) [UCP,](https://docs.docker.com/ee/ucp/) [Docker on AWS](https://docs.docker.com/docker-for-aws/) and possibly [on premises HA config](https://docs.docker.com/engine/swarm/admin_guide/#add-manager-nodes-for-fault-tolerance)
- [Describe and demonstrate how to configure backups for UCP and DTR.](https://docs.docker.com/datacenter/ucp/2.2/guides/admin/backups-and-disaster-recovery/)
- [Describe and demonstrate how to configure the Docker daemon to start on boot.](https://docs.docker.com/install/linux/linux-postinstall/)

### Domain 4: Networking (15% of exam)
- [Describe and demonstrate how to create a Docker bridge network for developers to use for their containers.](https://docs.docker.com/network/network-tutorial-standalone/)
- [Troubleshoot container and engine logs to understand a connectivity issue between
containers](https://success.docker.com/article/troubleshooting-container-networking)
- [Publish a port so that an application is accessible externally](https://github.com/wsargent/docker-cheat-sheet#exposing-ports)
- [Identify which IP and port a container is externally accessible on.](https://docs.docker.com/engine/reference/commandline/port/#examples)
- [Describe the different types and use cases for the built-in network drivers](https://blog.docker.com/2016/12/understanding-docker-networking-drivers-use-cases/)
- [Describe the Container Network Model and how it interfaces with the Docker engine and network and IPAM drivers.](https://success.docker.com/article/networking)
- [Describe and demonstrate how to configure Docker to use external DNS.](https://gist.github.com/Evalle/7b21e0357c137875a03480428a7d6bf6)
- [Describe and demonstrate how to use Docker to load balance HTTP/HTTPs traffic to an application (Configure L7 load balancing with Docker EE)](https://docs.docker.com/datacenter/ucp/2.2/guides/admin/configure/use-a-load-balancer/#configuration-examples)
- [Describe the types of traffic that flow between the Docker engine, registry and UCP controllers.](https://success.docker.com/article/networking/)
- [Describe and demonstrate how to deploy a service on a Docker overlay network.](https://docs.docker.com/network/overlay/)
- Describe the difference between "host" and "ingress" port publishing mode ([Host](https://docs.docker.com/engine/swarm/services/#publish-a-services-ports-directly-on-the-swarm-node), [Ingress](https://docs.docker.com/engine/swarm/ingress/))
- [Describe how to route traffic to Kubernetes pods using ClusterIP and NodePort services.](https://docs.docker.com/ee/ucp/kubernetes/)
- [Describe the Kubertnetes’ container network model](https://kubernetes.io/docs/concepts/cluster-administration/networking/)


### Domain 5: Security (15% of exam)
- Describe security administration and tasks.
- [Describe the process of signing an image](https://docs.docker.com/engine/security/trust/content_trust/#push-trusted-content)
- [Describe and demonstrate that an image passes a security scan.](https://docs.docker.com/datacenter/dtr/2.5/guides/admin/configure/set-up-vulnerability-scans/)
- [Describe and demonstrate how to enable Docker Content Trust.](https://docs.docker.com/engine/security/trust/content_trust/)
- [Describe and demonstrate how to configure RBAC with UCP.](https://docs.docker.com/datacenter/ucp/2.2/guides/access-control/)
- [Describe and demonstrate how to integrate UCP with LDAP/AD.](https://docs.docker.com/datacenter/ucp/2.2/guides/admin/configure/external-auth/)
- [Describe and demonstrate how to create UCP client bundles.](https://blog.docker.com/2017/09/get-familiar-docker-enterprise-edition-client-bundles/)
- [Describe default engine security](https://docs.docker.com/engine/security/security/)
- [Describe swarm default security](https://docs.docker.com/engine/swarm/how-swarm-mode-works/pki/)
- [Describe MTLS](https://diogomonica.com/2017/01/11/hitless-tls-certificate-rotation-in-go/)
- [Describe identity roles.](https://docs.docker.com/datacenter/ucp/2.2/guides/access-control/permission-levels/#roles)
- [Compare and contrast UCP workers and managers.](https://docs.docker.com/datacenter/ucp/2.2/guides/architecture/)
- Describe process to use external certificates with UCP and DTR (**UCP** [from cli](https://success.docker.com/article/how-do-i-provide-an-externally-generated-security-certificate-during-the-ucp-command-line-installation), [from GUI](https://docs.docker.com/ee/ucp/admin/configure/use-your-own-tls-certificates/#configure-ucp-to-use-your-own-tls-certificates-and-keys), [print the public certificates](https://docs.docker.com/datacenter/ucp/3.0/reference/cli/dump-certs/)), [**DTR**](https://docs.docker.com/ee/dtr/admin/configure/use-your-own-tls-certificates/))

### Domain 6: Storage and Volumes (10% of exam)
- [Identify the correct graph drivers to uses with various operating systems.](https://docs.docker.com/storage/storagedriver/select-storage-driver/)
- [Describe and demonstrate how to configure devicemapper.](https://docs.docker.com/storage/storagedriver/device-mapper-driver/#configure-docker-with-the-devicemapper-storage-driver)
- [Compare object storage to block storage, and explain which one is preferable when
available](https://rancher.com/block-object-file-storage-containers/)
- [Describe how an application is composed of layers and where these layers reside on the filesystem.](https://docs.docker.com/storage/storagedriver/#images-and-layers)
- [Describe the use of volumes are used with Docker for persistent storage.](https://docs.docker.com/storage/volumes/)
- Identify the steps you would take to clean up unused images on a filesystem, also on DTR.
([image prune](https://docs.docker.com/engine/reference/commandline/image_prune/), [system prune](https://docs.docker.com/engine/reference/commandline/system_prune/) and [from DTR](https://docs.docker.com/ee/dtr/user/manage-images/delete-images/))
- [Describe and demonstrate how storage can be used across cluster nodes.](https://docs.docker.com/engine/extend/legacy_plugins/#volume-plugins)
- Describe how to provision persistent storage to a Kubernetes pod using persistentVolumes.
- Describe the relationship between container storage interface drivers, storageClass, persistentVolumeClaim and volume objects in Kubernetes

## Quick facts about the exam

  ### Summary
  These are the most relevant quick facts of the exam:

  - The exam is online, using Google Chrome browser on <B>Windows</B> or <B>MacOS</B> ONLY. <B>Linux</B> support IS NOT available at this time;
  - 55 questions to be answered within 90 minutes. Which give you almost one minute and a half to spend on each question;
  - It costs 195 USD or 175 EUR;
  - Lasts for 2 years after the day you got certified;
  - Docker does not publish exam passing scores because exam questions and passing scores are subject to change without notice;
  - Results comes instantly.

  More detailed parts about the exam, please refer to the Links section.

  ### Question format

  All the questions follow this strucuture: ONE question and FOUR different possible answers.

  With that in mind, there are TWO TYPES of giving answers:
  - ONE RIGHT ANSWER: The answer options will be a clickable spot and you must select ONE CHOICE. This can be either select a valid answer in a true/false statement or a fill in blank example.
  - MULTIPLE ANSWERS: The answer option will be a square-type and accepts MULTIPLE CHOICES. Before checking the answers, please refer to the question to ensure HOW MANY VALID CHOICES ARE.

  There are no boolean questions (statement and then choose between True or False).

## Links

- [About the exam](https://success.docker.com/Certification)
- [Official study guide (PDF)](https://docker.cdn.prismic.io/docker/3f8ef3b3-87f1-47c7-b820-0e0a8bb308d4_DCA_study_guide_+v1.1+pdf.pdf)

## Contributors

Thanks to all [contributors!](https://github.com/Evalle/DCA/graphs/contributors)

