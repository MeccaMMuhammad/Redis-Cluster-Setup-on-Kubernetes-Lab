# Redis-Cluster-Setup-on-Kubernetes-Lab
This repository contains a step-by-step guide for setting up a Redis Cluster on Kubernetes.
It includes creating Persistent Volumes (PVs), configuring StatefulSets, exposing the Redis service, and finally setting up the Redis cluster itself. This lab has been an excellent way to solidify my knowledge of Kubernetes, Linux system administration, and cloud-native technologies.

Table of Contents
Setting Up Persistent Volumes (PVs)

Creating a Redis Service

Configuring StatefulSets

Creating the Redis Cluster

5. Final Notes and Challenges

Persistent Volumes & Claims: I gained a better understanding of how Kubernetes handles storage for stateful applications like Redis. This step was crucial for ensuring that data persists across pod restarts.

StatefulSets: Deploying Redis with StatefulSets allowed me to maintain stable identities for each Redis pod, which is essential for creating a reliable Redis cluster.

Cluster Communication: Configuring the service with specific ports (client and gossip) and setting up a headless service was essential for Redis nodes to discover and communicate with each other.

This lab has been a great learning experience in scaling Redis on Kubernetes. It reinforced my understanding of Kubernetes concepts like StatefulSets, Persistent Volumes, and Services while also emphasizing best practices for high-availability and fault-tolerant systems.

