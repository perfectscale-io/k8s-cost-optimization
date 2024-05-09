title: The Kubernetes Cost Optimization Guide
# Balancing Cost with Performance and Reliability

Kubernetes cost optimization comes down to pinpointing the correct resource allocations and auto-scaling factors for our workloads.

But "correct" in this context doesn't mean "the least possible amount of resources". It's a delicate interplay of cost vs. performance vs.reliability. 

In order to run our clusters in the most cost-effective way without compromising either performance or reliability it's vitally inportant to understand the Pod QoS model and the implications of PodDisruptionBudget.


## Understanding the Pod QoS Model

Kubernetes cost optimization starts with correct resource allocation for application containers that Kubernetes orchestrates.

Each container can have requests and limits defined for either memory or cpu or both. 


- PodDisruptionBudget and application disruption