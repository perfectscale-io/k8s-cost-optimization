title: The Kubernetes Cost Optimization Guide
# The Golden Signals

The 4 "golden signals" of Kubernetes Cost Optimization as defined in a [whitepaper](https://services.google.com/fh/files/misc/state_of_kubernetes_cost_optimization.pdf) released by Google Cloud in June 2023.

| Signal                 | Group |
|------------------------|--------|
|1.Workload Rightsizing   |Resources |
|2.Demand-based Downscaling|
| 3.Cluster Bin Packing    |
|4.Cloud Provider Discount Coverage | Cloud Discounts |


These signals help us apply and measure cost optimization for Kubernets clusters. 

The 3 signals in the *resources* group apply to all clusters  - be it on-prem or on-cloud. 

The *cloud discounts* naturally only apply to cloud-based managed clusters, where it is very important to pinpoint the instance types and reservation level of our cluster nodes.

Let's explain each signal in a bit more detail.

#### The Resources Group

| Signal                    | Explanation              |
|---------------------------|--------------------------|
| Workload Rightsizing      | Refers to our ability to<br> allocate the amount of resources <br> that the workloads actually need and adapt<br>  resource requests and limits<br>  as application requirements change.
| Demand based autoscaling  | Measures the capacity of developers <br>and platform admins to make clusters <br> scale down during off-peak hours.                         |
| Cluster bin packing       | Refers to our ability to<br> measure and utilize the CPU <br>and memory of each node <br>in the most effective and reliable way<br>through correct Pod placement. |

<br>
#### The Cloud Discounts group
|Signal |Explanation| 
|-------------------------|-----------------------------------------|
| Cloud Discount Coverage | Refers to leveraging cloud  VM instances that offer <br> discounts, such as Spot VMs, <br>as well as the ability of budget<br> owners and FinOps professionals to take <br>advantage of long-term continuous use discounts<br> offered by cloud providers.|






