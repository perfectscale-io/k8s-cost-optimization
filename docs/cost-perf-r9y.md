title: The Kubernetes Cost Optimization Guide
# Balancing Cost with Performance and Reliability

Kubernetes cost optimization comes down to pinpointing the correct resource allocations and auto-scaling factors for our workloads.

But "correct" in this context doesn't mean "the least possible amount of resources". It's a delicate interplay of cost vs. performance vs.reliability. 

In order to run our clusters in the most cost-effective way without compromising either performance or reliability it's vitally inportant to understand the Pod QoS model and the implications of PodDisruptionBudget.


- Understanding the Pod QoS Model https://services.google.com/fh/files/misc/state_of_kubernetes_cost_optimization.pdf
- PodDisruptionBudget and application disruption