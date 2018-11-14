# Ubuntu Docker base image    
===    

#### A demonstration of building and vulnerability scanning an OS Base Docker image    
Has multiple (69) Vulnerable components - Ubuntu 16.04 with a shell. 

Changing docker file to use newer ubuntu 18.04 image will show less (42) vulnerabilities.

The idea with this image is to push it into GCR Google Cloud Repository where the 
vulnerability management scanner can function.

Container Analysis provides vulnerability information for the container images in Container Registry.

This page describes how to view, filter, and get notifications on vulnerabilities for the images in Container Registry.

https://cloud.google.com/container-registry/docs/get-image-vulnerabilities

