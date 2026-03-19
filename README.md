# Performance Evaluation of Mesh Infrastructures in Kubernetes

## Overview
This repository contains my Bachelor's Thesis in Computer Engineering from the University of Bologna. 
The research focuses on analyzing and comparing two prominent Service Mesh technologies: **Istio** and **Network Service Mesh (NSM)**.

## Abstract
The transition to Cloud Computing and microservices has increased the complexity of service interactions. This thesis explores how Service Mesh solutions manage communication, security, and observability transparently. 
The study highlights the architectural differences:
- **Istio**: A mature L4/L7 Service Mesh based on the Envoy sidecar proxy, ideal for advanced traffic management.
- **NSM**: An L2/L3 infrastructure focused on network service abstraction and legacy system integration.

## Experimental Results
The practical section involves tests conducted on a **K3s** cluster to measure:
- Resource consumption (CPU and RAM) of Control Planes.
- Startup times for different configurations.
- Network performance (Throughput and Latency) using HTTP, TCP, and gRPC protocols.
- Resilience and healing capabilities during Data Plane failures.

Key findings show that while Istio offers superior reliability and traffic control, NSM provides unique connectivity advantages for legacy infrastructures, albeit with higher resource demands in specific configurations like vL3.

## Author
**Ulisse Steccanella**
Academic Year: 2024/2025
Supervisor: Prof. Antonio Corradi
